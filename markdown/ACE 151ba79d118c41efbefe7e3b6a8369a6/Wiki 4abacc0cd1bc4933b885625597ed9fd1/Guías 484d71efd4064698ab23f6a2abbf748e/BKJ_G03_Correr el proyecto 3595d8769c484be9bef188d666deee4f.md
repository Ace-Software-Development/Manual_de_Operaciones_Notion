# BKJ_G03_Correr el proyecto

## Prerrequisitos

- Haber clonado el repositorio

[](https://github.com/Ace-Software-Development/blackjack_monarca)

- Haber instalado pm2 (ver guía)

[Instalación de pm2](BKJ_G01_Gui%CC%81a%20del%20servidor%2076ffad5f45c54fdabea9d5c68909c8ca/Instalacio%CC%81n%20de%20pm2%20d06ff367d4624a51afb995e6e12bb402.md) 

## Cliente

1. Entrar a la carpeta c*lient* del proyecto e instalar los paquetes del proyecto

```cpp
cd client
npm install
```

1. Correr el cliente

```cpp
npm start
```

## Servidor

1. Abrir una nueva terminal
2. Entrar a la carpeta *server* e instalar los paquetes del proyecto

```cpp
cd server
npm install
```

1. Descarga el archivo *dev_capullo.json*

[dev_capullo.json](https://drive.google.com/file/d/1ZV965uwlXma8qOXvWAzm0IVBoMOl0eoB/view?usp=sharing)

1. Guarda el archivo *dev_capullo.json* en la carpeta *server.* Recuerda no compartir estos archivos con nadie.
2. Corre el proyecto

```bash
pm2 start dev_capullo.json
```

1. **IMPORTANTE:** Cuando termines de correr el proyecto, debes de detener el proceso que corre en pm2 y borrarlo para que no siga consumiendo recursos. Además, pm2 se puede dañar si reinicias tu computadora mientras hay un proceso corriendo.

```bash
pm2 stop dev_capullo.json
pm2 delete dev_capu
```

## Acceder a la app

- Para ver la **aplicación** debes de buscar en tu navegador *localhost:3000/inicio*
- Para acceder al **dashboard** escribe *[localhost:8888/dashboard](http://localhost:8888/dashboard) en tu navegador*
    - User: user
    - Password: pass

## Bitácora de cambios

[Untitled](BKJ_G03_Correr%20el%20proyecto%203595d8769c484be9bef188d666deee4f/Untitled%20Database%20e1d334e1479a4394b4a8913d7ffb0ac6.csv)