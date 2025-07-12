# Programacion_R

# Explorador Web de Datos con R y Shiny

Este proyecto corresponde al examen de la asignatura "Programación con R" del Magíster en Data Science (UDLA). La aplicación permite cargar datasets, analizarlos, visualizarlos y obtener resúmenes automáticos con ayuda de IA (local o vía API).

## Objetivo General

Desarrollar una plataforma web interactiva que permita a cualquier usuario cargar un dataset y, a partir de su estructura, generar gráficos personalizados de forma automática, favoreciendo una toma de decisiones basada en evidencia.

## Tecnologías utilizadas

- R
- Shiny
- Tidyverse
- Vroom
- HTTR, JSONlite (para conexión con API de IA)
- testthat (para validación)
- AWS EC2 (Linux)

## Funciones destacadas

### `read_csv_auto(file)`

Detecta automáticamente el delimitador del archivo `.csv` entre `, ; \t |` y lo carga como `data.frame`.

### Otras funcionalidades

- Filtros dinámicos
- Visualización con ggplot2
- IA local automática al cargar el dataset
- Análisis por API bajo demanda

## Pruebas unitarias

Se implementaron pruebas unitarias con el paquete `testthat` para verificar el correcto funcionamiento de la función `read_csv_auto()` y casos de error.

## Dataset

El archivo utilizado para pruebas y visualización se encuentra disponible en:

https://github.com/ggalanc/Programacion_R/blob/main/Catedra_1/student_habits_performance.csv


## Autor

Gerardo Galán y Mabel Herrera
Magíster en Data Science, UDLA
