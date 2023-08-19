## Auth API

Esta aplicación te permite implementar una solución sencilla de inicio de sesión, construida utilizando el framework Nest y potenciada con autenticación JWT para garantizar una experiencia segura. La aplicación aprovecha la flexibilidad de Docker, empleando servicios tanto para la imagen de la aplicación como para una imagen de MongoDB, que sirve como base de datos.

## Cómo Iniciar la Aplicación
Sigue estos pasos para iniciar la aplicación en tu entorno local:

1. Instala las dependencias de la aplicación utilizando npm:
```bash
  npm install
```

2. Renombra el archivo `.env.template` a `.env` y reemplaza las variables correspondientes.

3. Inicia la aplicación:
```bash
  # development
  $ npm run start

  # watch mode
  $ npm run start:dev

  # production mode
  $ npm run start:prod
```

4. Accede a la aplicación desde http://localhost:3000.

## Ejecución con Docker
Si deseas desplegar la aplicación utilizando Docker, aquí te presento los pasos necesarios:

1. Asegúrate de tener Docker instalado en tu máquina.

2. Abre una terminal y navega hasta la raíz del proyecto.

3. Ejecuta Docker Compose:
```bash
  docker-compose up
```

Siguiendo estos pasos, lograrás que la aplicación Auth API se encuentre operativa en un contenedor Docker.
