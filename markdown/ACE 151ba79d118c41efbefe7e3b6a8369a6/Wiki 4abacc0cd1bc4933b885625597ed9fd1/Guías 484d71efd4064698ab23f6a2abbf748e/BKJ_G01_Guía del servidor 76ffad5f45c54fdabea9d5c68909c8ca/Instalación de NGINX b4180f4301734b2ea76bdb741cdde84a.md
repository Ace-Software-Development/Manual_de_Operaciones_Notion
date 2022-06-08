# Instalación de NGINX

## Prerrequisitos

Conectarse al servidor de Aluminio Monarca siguiendo la guía [Conectarse al servidor](Conectarse%20al%20servidor%20b1c883942674456e87cbb250e7283227.md).

## Instalación

`sudo apt update
sudo apt install nginx`

## Configuración general

sudo nano /etc/nginx/sites-available/capullo

```cpp
server {

        server_name monarca.inventario.com;

        location / {
                proxy_pass http://localhost:8888;
								proxy_https_version 1.1;
								proxy_set_header Upgrade $https_upgrade;
								proxy_set_header Connection 'upgrade';
								proxy_set_header Host $host;
								proxy_cache_bypass $https_upgrade;
        }
} 
```

sudo ln -s /etc/nginx/sites-available/capullo /etc/nginx/sites-enabled/

sudo nano /etc/nginx/nginx.conf

```cpp
http {
    . . .

    server_names_hash_bucket_size 64;

    . . .
}
```

## SSL con Lets encrypt

sudo apt install certbot python3-certbot-nginx

sudo ufw status

sudo ufw allow 'Nginx Full'
sudo ufw delete allow 'Nginx HTTP'

sudo certbot --nginx -d monarca.inventario.com
2

sudo systemctl status certbot.timer

sudo certbot renew --dry-run