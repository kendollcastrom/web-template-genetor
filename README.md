# Web Template Bundle

Este proyecto es un starter kit para desarrollar proyectos web utilizando **Webpack** como herramienta de construcción. Incluye configuraciones básicas para compilar y componer HTML utilizando Pug, CSS utilizando SCSS y JavaScript utilizando Babel. Además, cuenta con un servidor de desarrollo local que se puede ejecutar con Live Server y una configuración para construir una versión optimizada del proyecto para producción. La estructura de carpetas del proyecto está diseñada para una mejor organización y escalabilidad del código.

## Instalación
1. Clonar este repositorio.
2. Ejecutar **npm install** en la carpeta raíz del proyecto.
3. Ejecutar **npm run dev** para iniciar el servidor local.

## Uso
Estructura de carpetas
.
├── src
│   ├── js
│   │   ├── components
│   │   ├── index.js
│   │   └── utils
│   ├── styles
│   │   ├── abstracts
│   │   ├── base
│   │   ├── components
│   │   ├── layout
│   │   ├── pages
│   │   ├── themes
│   │   ├── vendors
│   │   └── main.scss
│   └── templates
│       ├── includes
│       ├── layouts
│       └── pages
├── public
│   ├── index.html
│   ├── bundle.js
│   └── styles.css
├── webpack.config.js
└── package.json

## Comandos de NPM
- **npm run dev**: Inicia el servidor local en **http://localhost:3000** y habilita la recarga automática del navegador cuando se guardan cambios en los archivos.
- **npm run build**: Genera una versión optimizada del proyecto en la carpeta public.

## Contribuir
- Crear un fork del repositorio.
- Crear una rama con la nueva funcionalidad o corrección de error.
- Realizar los cambios y confirmarlos.
- Enviar un pull request a la rama principal del repositorio.

## Crear commits
Escribir buenos mensajes de commit es importante para que el histórico de tu proyecto sea **legible**, **fácilmente escaneable** y, **claro**, entendible por cualquier persona que participe en el proyecto. **Todos los commits se harán en Inglés**.

[Commits Midudev](https://midu.dev/buenas-practicas-escribir-commits-git/)

## Licencia
MIT License

Copyright (c) [2023] [KendollCastro]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
