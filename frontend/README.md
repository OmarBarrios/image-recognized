# Clasificación de imágenes (perros y gatos)

Este código sirve como para la creación de un clasificador de perros y gatos usando Python y Tensorflow.

Este código representa el frontend, una vez que se crea y entrena el modelo de inteligencia artificial con Python y Tensorflow, el cual es exportado a los archivos "json" y "bin".

## Cómo utilizarlo

### Inicia un servidor en la carpeta
Una vez descargado el repositorio, este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso podemos utilizar cualquier servidor, para hacerlo localmente:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000