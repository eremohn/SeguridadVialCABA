<p align="center">
<img src="../Informe/Imagenes/Banner_informe.jpg"  >
</p>


## Introducción
---

Los siniestros viales representan una preocupación significativa en entornos urbanos como
Buenos Aires, con consecuencias que van desde daños materiales hasta pérdidas humanas. En este
contexto, el Observatorio de Movilidad y Seguridad Vial (OMSV) solicita un análisis de datos sobre los
accidentes viales ocurridos en la ciudad entre 2016 y 2021. Este análisis tiene como objetivo identificar
patrones y factores de riesgo para informar la implementación de medidas que reduzcan la cantidad de
víctimas fatales.
En Argentina, los siniestros viales constituyen una de las principales causas de muerte violenta, con un
promedio de cerca de 4.000 víctimas fatales por año. El presente informe se enfoca en el análisis de
datos proporcionados por el OMSV, con la meta de generar recomendaciones basadas en evidencia que
contribuyan a mejorar la seguridad vial en Buenos Aires.

## Metodología de trabajo
---

Para llevar a cabo el análisis de los datos de siniestros viales en la Ciudad de Buenos Aires, se siguió
una metodología de trabajo estructurada en varias etapas, abarcando desde la extracción y
transformación de los datos hasta la identificación de posibles anomalías y la preparación del conjunto
de datos para su análisis.

### 1. Transformación de la Base de Datos a DataFrames:
• Se importaron las librerías necesarias, principalmente pandas, para manejar los datos en
Python.
• Los datos fueron cargados desde archivos Excel en dos DataFrames distintos: df_victimas y
df_hechos .
• Se realizó una fusión de estos DataFrames utilizando la columna 'ID_hecho' como clave de
unión.
• Se reordenaron y renombraron las columnas para una mejor comprensión y consistencia en los
datos.

### 2. Exploración de los Datos:
• Se realizó una exploración inicial de los DataFrames para comprender su estructura y
contenido.
• Se verificó la presencia de valores nulos o faltantes en los datos y se tomó nota de la cantidad
de registros en cada DataFrame.
• Se identificaron los tipos de datos presentes en las columnas y se analizó la distribución de
valores en cada una de ellas.




