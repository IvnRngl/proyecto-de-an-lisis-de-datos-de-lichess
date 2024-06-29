# Proyecto de análisis de datos de Lichess

## Descripción

Este es un proyecto de análisis de datos donde uso la base de datos de Lichess para Noviembre del 2023.

Uso archivos csv, código SQL y Python. Todo el código relevante y descripciones paso a paso se encuentran en el archivo notebook.ipynb.

Finalmente, el archivo main.pdf (hecho con LaTeX) muestra visualizaciones de cifras clave.

## Proceso

Lichess da acceso a su base de datos [aquí](https://database.lichess.org/).

Primero descargué el archivo pgn para Noviembre del 2023.

Use la librería chess de Python para navegar el archivo pgn, extraer juegos individuales y guardar los metadatos relevantes en una tabla de MySQL.

Usando código SQL y la extensión SQLTools de VScode para crear archivos csv necesarios.

Finalmente, con Python y dataframes de Pandas, contesté preguntas simples sobre los juegos del primero de Noviembre.

## Clarificaciones

Debido a las restricciones de GitHub para el tamaño de archivos, no puedo subir el csv para todos los juegos del primero de Noviembre. En lugar de eso subí un pickle comprimido sin las últimas dos horas. Sin embargo, el archivo notebook.ipynb muestra el método que usé para tener los mismos datos.
