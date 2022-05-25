# Instalación de MongoDB

1. Actualizar la lista de paquetes e instalar los paquetes básicos
`sudo apt-get update
 sudo apt-get install build-essential`
2. Instalar node con nvm
`curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh) | bash
source ~/.profile
nvm i 16.14.2
node -v
nvm ls
nvm use 16.14.2`
3. Instalar MongoDB
    
    `wget -qO - [https://www.mongodb.org/static/pgp/server-5.0.asc](https://www.mongodb.org/static/pgp/server-5.0.asc) | sudo apt-key add -
    echo "deb [ arch=amd64,arm64 ] [https://repo.mongodb.org/apt/ubuntu](https://repo.mongodb.org/apt/ubuntu) bionic/mongodb-org/5.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-5.0.list
    sudo apt-get update
    sudo apt-get install -y mongodb-org`
    
4. Comandos de MongoDB en servidor con Linux nativo
    - *Correr MongoDB*
    `sudo systemctl start mongod`
    - *Verificar que corrió*
    `sudo systemctl status mongod`
    - *Detener MongoDB*
    `sudo systemctl stop mongod`
    - *Reiniciar MongoDB*
    `sudo systemctl restart mongod`
5. Para correr MongoDB en máquina virtual
[https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database)
`curl [https://raw.githubusercontent.com/mongodb/mongo/master/debian/init.d](https://raw.githubusercontent.com/mongodb/mongo/master/debian/init.d) | sudo tee /etc/init.d/mongodb >/dev/null
sudo chmod +x /etc/init.d/mongodb`
- *Correr MongoDB*
`sudo service mongodb start`
- Detener *MongoDB*
`sudo service mongodb stop`
- *Ver si corrió MongoDB*
`sudo service mongodb status`

### Arreglar error 14 de MongoDB

```
sudo chown -R mongodb:mongodb /var/lib/mongodb
sudo chown mongodb:mongodb /tmp/mongodb-PUERTO.sock
sudo service mongod restart
```