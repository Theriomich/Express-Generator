# Proyecto: Aplicación Web Básica con Express Generator y EJS

Este es un proyecto básico de una aplicación web creada con Express Generator y utilizando plantillas EJS. El proyecto sirve como ejemplo de cómo estructurar una aplicación web con Express y EJS.

## Descripción

Este proyecto muestra cómo configurar una aplicación web utilizando Express Generator. Se ha utilizado el motor de plantillas EJS para generar las vistas de la aplicación. La aplicación básica incluye rutas para la página principal y una página de ejemplo.

## Requisitos

- Node.js
- npm (Node Package Manager)
- Express Generator (para crear la estructura del proyecto)

## Instalación

1. Instala Express Generator de manera global si aún no lo tienes:
    ```sh
    npm install -g express-generator
    ```

2. Crea una nueva aplicación llamada `appweb` utilizando Express Generator con EJS como motor de plantillas:
    ```sh
    express --view=ejs appweb
    ```

3. Navega al directorio del proyecto:
    ```sh
    cd appweb
    ```

4. Instala las dependencias necesarias:
    ```sh
    npm install
    ```

## Uso

1. Inicia el servidor:
    ```sh
    npm start
    ```

2. Abre tu navegador y navega a `http://localhost:3000` para ver la página principal de la aplicación.

## Estructura del Proyecto

La estructura del proyecto generada por Express Generator es la siguiente:

appweb/
├── bin/
│ └── www
├── public/
│ ├── images/
│ ├── javascripts/
│ └── stylesheets/
│ └── style.css
├── routes/
│ ├── index.js
│ └── users.js
├── views/
│ ├── error.ejs
│ ├── index.ejs
│ └── layout.ejs
├── app.js
├── package.json
└── README.md

markdown
Copiar código

## Explicación del Código

- **`app.js`**: El archivo principal de la aplicación que configura el servidor Express.
- **`bin/www`**: El archivo que inicia el servidor.
- **`routes/index.js`**: Define las rutas para la página principal.
- **`routes/users.js`**: Define las rutas para la página de usuarios.
- **`views/`**: Contiene las vistas EJS que se utilizan para renderizar las páginas web.
- **`public/`**: Contiene archivos estáticos como imágenes, JavaScript y CSS.

## Personalización

Puedes personalizar las vistas editando los archivos en la carpeta `views`. Por ejemplo, para cambiar el contenido de la página principal, edita `views/index.ejs`.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cualquier cambio importante antes de enviar un pull request.