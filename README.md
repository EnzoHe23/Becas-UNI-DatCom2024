# Proyecto especial: Becas para estudiantes de la UNI (08/08 - 05/09)

### Para el análisis

[![Javascript](https://img.shields.io/badge/Clic%20para%20abrir-Power%20BI%20dashboard-yellow.svg)](https://app.powerbi.com/view?r=eyJrIjoiMmJkZTJiNjktM2MzNi00NmNhLTk5OWEtMWJmOGU0MjU1NDZjIiwidCI6IjBlMGNiMDYwLTA5YWQtNDlmNS1hMDA1LTY4YjliNDlhYTFmNiIsImMiOjR9)
[![Javascript](https://img.shields.io/badge/Clic%20para%20abrir-Google%20Colaboratory-orange.svg)](https://colab.research.google.com/drive/1TSI0C-4jdSA9TzLkCOL6lXWZ0c_zXpzL?usp=sharing)

Haga clic en los badges de arriba ('Clic para abrir Power BI dashboard' o 'Clic para abrir Google Colaboratory'). Si no le funcionan los links, puede hacer click en los enlaces resaltados para entrar al [dashboard en Power BI](https://app.powerbi.com/view?r=eyJrIjoiMmJkZTJiNjktM2MzNi00NmNhLTk5OWEtMWJmOGU0MjU1NDZjIiwidCI6IjBlMGNiMDYwLTA5YWQtNDlmNS1hMDA1LTY4YjliNDlhYTFmNiIsImMiOjR9) y al [Google Colab](https://colab.research.google.com/drive/1TSI0C-4jdSA9TzLkCOL6lXWZ0c_zXpzL?usp=sharing) del análisis.

### Para el prototipo de solución

[![Javascript](https://img.shields.io/badge/Clic%20para%20abrir-Power%20BI%20dashboard-yellow.svg)](https://app.powerbi.com/view?r=eyJrIjoiOTllZmIxMjEtMTAzYS00N2EwLWFlMTUtODM3Y2ZiNzBlMjQzIiwidCI6IjBlMGNiMDYwLTA5YWQtNDlmNS1hMDA1LTY4YjliNDlhYTFmNiIsImMiOjR9)
[![Javascript](https://img.shields.io/badge/Clic%20para%20abrir-Google%20Colaboratory-orange.svg)](https://colab.research.google.com/drive/15QivZfFC8UZ-Q7NikX3S-1Dhn7I9pzEr?usp=sharing)

Haga clic en los badges de arriba ('Clic para abrir Power BI dashboard' o 'Clic para abrir Google Colaboratory'). Si no le funcionan los links, puede hacer click en los enlaces resaltados para entrar al [dashboard en Power BI](https://app.powerbi.com/view?r=eyJrIjoiOTllZmIxMjEtMTAzYS00N2EwLWFlMTUtODM3Y2ZiNzBlMjQzIiwidCI6IjBlMGNiMDYwLTA5YWQtNDlmNS1hMDA1LTY4YjliNDlhYTFmNiIsImMiOjR9) y al [Google Colab](https://colab.research.google.com/drive/15QivZfFC8UZ-Q7NikX3S-1Dhn7I9pzEr?usp=sharing) del análisis.

## Resumen

El proyecto busca aplicar análisis de datos para descubrir patrones en estudiantes que poseen un alto rendimiento académico. Para ello, se utilizó el dataset ofrecido por la Universidad Nacional de Ingeniería en la página de Datos Abiertos, que contenía información de las matrículas registradas desde el semestre 2016-1 hasta el 2024-1. Se utilizó Google Colaboratory, donde se aplicó limpieza de datos al dataset para obtener la información más importante de éste, y después se utilizó Power BI, donde se desarrolló el dashboard en el que se analizó los datos de manera efectiva. El prototipo de solución también es un dashboard en Power BI, que muestra los estudiantes que cumplen con lo necesario para ganarse una beca para maestría o doctorado.

## 📖 Contenidos 📖

1. [📰 Acerca del proyecto 📰](#-acerca-del-proyecto-)
2. [📃 Objetivos y preguntas 📃](#-objetivos-y-preguntas-)
3. [📊 Procedimientos 📊](#-procedimientos-)
4. [📝 Conclusiones e ideas post-análisis 📝](#-conclusiones-e-ideas-post-análisis-)
5. [💡 Solución propuesta 💡](#-solución-propuesta-)

## 📰 Acerca del proyecto 📰

El proyecto fue realizado durante la datatón **"Exprésate Perú con Datos 2024"**. Para este evento, se tuvo que elegir 1-2 datasets dentro de la página de **Datos Abiertos**, hallar patrones destacables y realizar un análisis mediante el uso de una tecnología, como un modelo predictivo o un tablero de control, por ejemplo.

Este proyecto utilizó el lenguaje de programación Python, dentro de un archivo de Jupyter Notebook. Como librerías utilizadas, tenemos:

- **Pandas**, para manejar la información del dataset principal mediante dataframes.
- **Matplotlib y pyplot**, para realizar gráficos que nos permita ver qué datos tenemos en cada columna del dataset, facilitando la corrección de información.
- **NumPy**, para realizar mediciones como los rangos para cada tasa de pobreza de acuerdo a un porcentaje.

Sin embargo, la visualización de datos final fue hecha con ayuda de un dashboard en Power BI.

Como fuente de datos, se utilizó los datasets del conjunto 'Alumnos matriculados en la Universidad Nacional de Ingeniería - [UNI]', ofrecidos por la **Universidad Nacional de Ingeniería - UNI**.

Página oficial de Datos Abiertos: https://www.datosabiertos.gob.pe/

Datasets y diccionario del conjunto utilizado: https://www.datosabiertos.gob.pe/dataset/alumnos-matriculados-en-la-universidad-nacional-de-ingenier%C3%ADa-uni

## 📃 Objetivos y preguntas 📃

Para este proyecto, hubo un objetivo principal: Hallar patrones comunes en estudiantes con alto rendimiento académico.

Hubieron 4 preguntas que se respondieron en este análisis:

1. ¿Cuál el Rendimiento Académico general por tasa de pobreza/facultad/rango de edad/modalidad de ingreso/estudiantes recientes?
2. ¿Cuántos son los estudiantes por tasa de pobreza/facultad/rango de edad/modalidad de ingreso/estudiantes recientes?
3. ¿Cuántos estudiantes no alcanzaron un alto rendimiento académico? ¿Cuál es su R. A. general?
4. ¿Por qué hay estudiantes con un rendimiento académico anormal?

## 📊 Procedimientos 📊

1) Se pasaron los datos de archivo .csv a un dataframe.
2) Se ordenaron las filas para mantener un buen orden en las matrículas.
3) Se removieron las columnas que no contaban con suficientes datos para llenar los valores nulos, y que no serían de utilidad para el análisis.
4) Se trató valores nulos y no-nulos para tener toda la información de manera adecuada.
5) Se crearon dos dataframes adicionales que ayuden con la visualización de datos en el dashboard.
6) Se descargaron los dataframes del Colab.
7) Se subieron los datasets a un dashboard en Power BI y se realizaron los toques finales a los datates.
8) Se crearon dos indicadores para el análisis general.
9) Se mejoró el análisis de información mediante varios gráficos.
    1. Un mapa que muestra los departamentos de domicilio de los estudiantes, con colores según la tasa de pobreza del departamento, y con tamaños según la cantidad de estudiantes que han vivido ahí.
    2. Un gráfico de barras que muestra las modalidades de ingreso por el número de estudiantes.
    3. Una tabla con la lista de estudiantes, por su ID, sexo, especialidad y Rendimiento Académico Actual.
    4. Un gráfico de embudo que muestra los rangos de edad por el número de estudiantes.
    5. Un gráfico para revisar los alumnos con un rendimiento académico de al menos un 80%.
12) Se dividió el dashboard en tres hojas: Menú Principal, General y Detallado.
13) Se realizaron medidas con DAX para la visualización de datos en el análisis detallado.
14) Se publicó el dashboard en la web de forma pública.

## 📝 Conclusiones e ideas post-análisis 📝

1. En caso de que no se trate de corrupción, hay serios problemas con el registro de los ciclos relativos en las matrículas de los estudiantes. Se necesita mejorar el sistema que registra los datos de matrícula.
2. Si bien el rendimiento académico puede indicar el potencial de los estudiantes para el aprendizaje, los valores exagerados pueden entorpecer la visión sobre este potencial, y hasta considerarlo irreal.
3. Las matrículas con R. A. anormales vienen mayormente de los estudiantes matriculados hasta el 2022-2. Para llevar a cabo posibles soluciones, sería más efectivo tomar en cuenta los datos de matrículas que continúen más allá del semestre 2022-2.

## 💡 Solución propuesta 💡

Con el fin de ayudar a lograr el Objetivo de Desarrollo Sostenible 4 (Educación de Calidad), hemos propuesto crear una app que facilite el registro de la información de las matrículas, que contenga un dashboard que muestre aquellos alumnos que cumplan con los requisitos necesarios para ser considerados aptos para una beca para maestría o doctorado. El prototipo de la solución SÓLO incluye el dashboard.

La solución ayudará con dos metas del ODS 4:
- Meta 3.4, ya que los estudiantes no serán discriminados por su sexo, y tendrán acceso a una buena calidad de educación universitaria pública.
- Meta 4.4, ya que busca evitar la deserción temprana por falta de dinero, y aumentar sustancialmente el número de jóvenes adultos con competencias profesionales y listos para conseguir un empleo decente o hacer un emprendimiento propio.
