# G12_Despliegue a Digital Ocean

## Objetivo

Desplegar una página web consumible en un dominio.

## **Criterios de entrada**

- Proyecto web con arquitectura Cliente-Servidor

## Prerrequisitos

- Tener la arquitectura completa (NodeJS, NGINX, etc.)
- Server y Client completo (ambos pueden correr)
- Entender el alcance de la BD (desarrollo y producción)
- Archivos de los ambientes de la base de datos listos
- Revisar que podemos conectarnos desde cualquier dispositivo a la base de datos de desarrollo
- Revisar que podemos conectarnos desde cualquier dispositivo a la base de datos de producción
- Montar SSL
- Full Access PROD

## Consideraciones

Para que los fetch de React funcionen al desplegar el proyecto se debe de eliminar http://localhost de su liga.

Antes:

![Untitled](G12_Despliegue%20a%20Digital%20Ocean%207f51737490994ee497f705cf87ef3718/Untitled.png)

Después:

![Untitled](G12_Despliegue%20a%20Digital%20Ocean%207f51737490994ee497f705cf87ef3718/Untitled%201.png)

Se recomienda utilizar una variable global que cambie cuando se está desarrollando y desplegando la aplicación.

## **Procedimiento**

**Prueba local**

1. Crear una nueva rama en el repositorio del proyecto

```cpp
git checkout develop
git pull
git checkout -b deploy
```

1. Entrar a la carpeta c*lient* del proyecto y realizar un build

```cpp
cd client
npm run build
```

1. Escribir las siguientes líneas en el app.js/index.js

```jsx
app.use(express.static(
	path.join(__dirname,
							"../client/build")));
//API aquí
app.get("*", (req, res) => {
	res.sendFile(
			path.join(__dirname,
						"../client/build/index.html")
	);
});
```

1. Abrir una nueva terminal
2. Entrar a la carpeta *server*

```cpp
cd server
```

1. Correr únicamente el servidor (no correr npm start en el cliente)

```cpp
pm2 start JSON //por ejemplo dev_capullo.json
```

1. Acceder a localhost:PuertoServer desde el navegador. Por ejemplo:

```cpp
localhost:8888/inicio
```

1. El navegador debe de mostrar la página web funcionando
2. Hacer commit y push de los cambios

```cpp
git add -A
git commit -m "Add deploy configuration in app.js"
git push
```

**Despliegue**

1. Acceder al servidor en el que se desplegará la página web siguiendo la guía para [Conectarse al servidor](BKJ_G01_Gui%CC%81a%20del%20servidor%2076ffad5f45c54fdabea9d5c68909c8ca/Conectarse%20al%20servidor%20b1c883942674456e87cbb250e7283227.md).
2. Clonar el repositorio en el servidor 

```cpp
git clone urlGithub //ejemplo https://github.com/Ace-Software-Development/blackjack_monarca.git
```

1. Ingresar a la rama creada en el paso 1

```cpp
git checkout deploy
```

1. Realizar un build nuevamente. Los builds son ignorados por Git.

```cpp
cd client
npm run build
```

1. Entrar a la carpeta del servidor y correr el proyecto

```cpp
cd ..
cd server
pm2 start dev_capullo.json
```

1. Ahora deberás de poder acceder a tu dominio y visualizar la página web desde cualquier dispositivo

## **Criterios de salida**

- Servidor con el proceso pm2 corriendo
- Página web accesible desde cualquier dispositivo

## **Responsable**

@Mariana Soto Ochoa 

## Bitácora de cambios

[Untitled](G12_Despliegue%20a%20Digital%20Ocean%207f51737490994ee497f705cf87ef3718/Untitled%20Database%207a08c922b5ec48a896a756f5ba08d542.csv)