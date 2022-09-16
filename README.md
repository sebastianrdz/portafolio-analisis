# portafolio-analisis

## Módulo 1 Técnicas de procesamiento de datos para el análisis estadístico y para la construcción de modelos. 
  > Archivo: _Modulo1_Salarios.ipybn_
### Preguntas
* ¿Cuál es el salario al que puede aspirar un analista de datos?
  > Un analista de datos puede aspirar a un salario promedio de 112297.8 USD.
* ¿Influye el nivel de experiencia en el salario?
  > Si, influye parcialmente. Por lo que podemos interpretar de las gráficas de arriba, los salarios rinden de un rango entre $0 - $250,000, siendo los del rango bajo los de nivel entrantes, seguidos por los de nivel medio, y luego por los de nivel senior. Los demás pocos casos que ganan mayor cantidades a estas están ligadas con los niveles ejecutivos.
* ¿Ha incrementado la demanda de analistas a lo largo del tiempo?
  > La demanda de empleo por lo general ha incrementado exponencialmente para todos los puestos desde el año 2020. La demanda por analistas está en la creciente teniendo un aumento de más del 100% en solo 2 años.

* ¿En qué países se ofrecen mejores salarios?
  > Por lo visto, Estados Unidos presenta los mejores salarios y en dólares.

---
### Resumen
Dentro de este análisis se hizo uso  de una implementación de regresión lineal con el propósito de predecir el salario de una dada persona basándonos en sus atributos como lo puede ser su compañía, su puesto, su experiencia, entre otros. Viendo á los procedimientos que se realizaron en esta práctica, lo primero que se realizó con los datos fue la visualización e interpretación de las variables las cuales son las siguientes:
1. work_year: Es el año en que la persona entró a trabajar.
2. experience_level: Es el nivel de experiencia de la persona.
3. employment_type: Es tipo de empleo, si es tiempo completo, medio tiempo, contratista o libre.
4. job_title: El título a la que la persona fue asignada en el trabajo.
5. salary: Salario de la persona.
6. salary_currency: Moneda en la que es pagado el empleado.
7. salary_in_us: Salario equivalente en USD
8. employee_residence: Residencia del empleado.
9. remote_ratio: Manera de trabajar del empleado (remoto, híbrido, presencial).
10. company_location: Lugar en el que está situado la compañía.
11. company_size: Tamaño de la compañía.

Ahora bien, lo que se hizo en primera instancia fue analizar variables cuantitativas de los datos. Entre estos analizamos el tipo de datos, la suma de datos, la media, desviación estándar, mínimo, máximo y la correlación.

Seguido de esto pasamos a analizar los atributos de una manera más cualitativa. Se realizaron diferentes gráficas para visualizar cómo están distribuidos las variables a través de todo el dataset. Entre estas el conteo de trabajadores y el año en el que entraron a trabajar, la distribución del salario entre los empleados, entre otras. Estas gráficas nos permiten visualizar las relaciones entre las variables y definir cuáles valores podemos modificar o incluso eliminar para ajustar nuestros modelos de la manera correcta.

Teniendo esto en cuenta, lo siguiente fue hacer una limpieza de los datos y ajustes a los datos con el propósito de analizar las variables cualitativas de una manera cuantitativa que nos permita definir un modelo más adecuado. Con estos valores entrenamos un modelo de regresión lineal el cual nos permite como ya mencione predecir el salario al que puede aspirar un empleado dado las variables que están definidas en la parte superior.

Como resultado obtuvimos un valor de predicción de 0.8733, lo que nos indica que de cada 100 predicciones que realicemos, el 87% de estas van a ser correctas. Se puede decir de una mejor manera que este modelo nos brinda un nivel de confianza del 87%.





## Módulo 2 Análisis y Reporte sobre el desempeño del modelo.
> Archivo: _Modulo2_AnálisisYReporte.pdf_

Todo el análisis se encuentra dentro del documento pdf.