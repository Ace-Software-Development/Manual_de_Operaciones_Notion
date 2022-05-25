# Instalación de NGINX

## Instalación

`sudo apt update
sudo apt install nginx`

## Configuración general

sudo nano /etc/nginx/sites-available/capullo

```cpp
server {
        listen 80;

        server_name monarca.inventario.com;

        location / {
                proxy_pass http://localhost:8888;
								proxy_http_version 1.1;
								proxy_set_header Upgrade $http_upgrade;
								proxy_set_header Connection 'upgrade';
								proxy_set_header Host $host;
								proxy_cache_bypass $http_upgrade;
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