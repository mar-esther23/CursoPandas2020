# Introducción al análisis y visualización de datos con python
## Mariana Esther Martínez Sánchez

Curso básico para análisis de tablas de datos usando python y pandas.

Impartido: 
* Pyladies-México 13 y 14 de febrero de 2020

## Requisitos:
* Saber usar R, SAS, STATA o Excel avanzado.
* Tener [anaconda](https://www.anaconda.com/distribution/) instalado.
* Acceso a internet.

## Índice

1. [Introducción a python](./CP-Introduccion.ipynb)
    1. Instalación de conda
    2. Jupyter notebooks
    3. Introducción a python

2. [Obtención de datos](./CP-ObtencionLimpieza.ipynb)
    1. Descargar datos abiertos
    2. ¿Qué es un dato?
    3. Cargar los datos en python
        * Ubicacion en la carpeta
        * Excel, csv, pickle

3. [Limpieza de datos](./CP-ObtencionLimpieza.ipynb)
    1. Pasos de un análisis de datos
    2. Exploración básica - pandas_profiling
    3. Operaciones básicas de pandas - slicing
        * Estructura de una tabla (index, columns, dtype, nan)
        * select column(s), row(s), head, tail, loc, iloc
        * sort
        * unique, nunique, value_counts
        * select by criteria (==, !=, isin, isna, notna, multiple statements)
    4. Limpieza de datos
        * Quitar columnas (drop, select)
        * Cambiar tipos de datos (datetime)
        * Modificar campos de texto (replace, title, unidecode)
        * Eliminar datos fuera de rango (map, replace)
        * Datos faltantes (fillna)
    5. Guardar datos
        * Excel y cs
 v       * pickle

4. [Gráficación básica](./CP-AnalisisGraficas.ipynb)
    1. Tipos de gráficas (lines, bars, scatter, hist)
    2. Elementos de una gráfica (title, axis, etc)
    3. matplotlib

5. [Análisis de datos](./CP-AnalisisGraficas.ipynb)
    1. Estadística básica (count, sum, mean, median, moda, std)
    2. Agrupamiento (groupby, filter, aggregate)
    3. Tablas pivote (pivot_table)
    4. Respondiendo preguntas

6. Extras
    1. Seaborn (distplot, heatmap, multiples)
    2. Estadística (corr, linear_regresion)
    3. Mapas (geopandas)
    4. Visualización de datos

## Recursos útiles
* Programación básica en python
    * Think like a computer scientist https://greenteapress.com/wp/think-python/
    * Introducción a la programación en Python I https://www.coursera.org/learn/aprendiendo-programar-python
* Programación intermedia en python
    * Guia estilo https://pep8.org/
    * Docstrings numpy https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_numpy.html
    * The Hacker's Guide to Python, Julien Danjou
    * Computer Science Distilled, Wladston Ferreira Filho
    * Estructuras de datos https://classroom.udacity.com/courses/ud513
* Visualización
    * Selección de colores http://colorbrewer2.org/
    * Fundamentals of Data Visualization https://serialmentor.com/dataviz/
    * Visualización de datos y D3  https://classroom.udacity.com/courses/ud507

* Estadística
    * Estadistica para Dummiens, Deborah J Rumsey
    * Understanding Advanced Statistical Methods,  Peter H. Westfall & Kevin S. S. Henning

* Machine learning
    * Machine Learning with Python: A Practical Introduction https://www.edx.org/course/machine-learning-with-python-a-practical-introduct

* <Aprendizaje 
    * Aprendiendo a aprender https://www.coursera.org/learn/learning-how-to-learn
