<div style="text-align:center"><img src="https://www3.um.edu.uy/logoum.jpg" width=300></div>
<h1 align="center">Introducción a la Ciencia de Datos</h1>
<h2 align="center"> <font color='gray'>Universidad de Montevideo</font></h2>

En este repositorio podrá encontrar el material necesario para poder llevar el curso con facilidad. Este repositorio consta de material teórico, material práctico, parciales anteriores, exámenes (con y sin solución) y material adicional (como notebooks para acompañar clases teóricas).

Índice

- 📌 [Descarga del repositorio](#descarga) 
- 📌 [Estructura del repositorio](#estructura_repositorio) 🌲
- 📌 [Syllabus](#syllabus) 📚
    - [Introducción](#introduccion) 🏁
    - [Datos](#datos) 💾
    - [Operaciones con tablas](#operaciones_tablas) 📋
    - [Análisis exploratorio I](#eda_1) 🧐
    - [Análisis exploratorio II](#eda_2) 🧐🧐
    - [Feature engineering](#feature_engineering) 👷🏼‍♂️
    - [Pruebas estadísticas](pruebas_estadisticas) 🧮
    - [Visualización de datos I](#visualizacion_1) 📈
    - [Visualización de datos II](#visualizacion_2) 📉
    - [Visualización de datos III](#visualizacion_3) 📊
    - [Regresión Lineal](#regresion) 🔢
    - [Modelos de clasificación](#clasificacion) 🌳
    - [Series de tiempo](#series_tiempo) ⏳
    - [Aprendizaje no supervisado](#unsupervised) 🁋
    - [Procesamiento de Lenguaje Natural](#nlp) 📘📗📕
    - [Validación](#validacion) 🎯
    - [Storytelling](#storytelling) 💬

<a class='anchor' id='descarga'></a><h1 style="text-align: center; background-color:powderblue; font-size:20px;">Descarga del repositorio</h1>

<div style="background-color:#ECFFFF">

Existen varias maneras para descargar el repositorio:
1. Code ---> Download ZIP.

<div style="text-align:center"><img src="https://i.ibb.co/whJV43G/UM.jpg" alt="UM" border="0"></div>

2. Si te sentis más cómodo con la terminal podes clonar el repositorio:
`git clone git@github.com:alejopaullier96/um-data-science.git`
</div>

<a class='anchor' id='estructura_repositorio'></a><h1 style="text-align: center; background-color:powderblue; font-size:20px;">Estructura del repositorio (Directory tree)</h1>
<div style="background-color:#ECFFFF">
A continuación se provee un diagrama general de los archivos y carpetas del curso para que usted se familiarice con el mismo. Tenga en cuenta que en el momento que usted curse esta materia la estructura puede haber cambiado ligeramente.

```
├── README.md
├── ejemplos_de_clase
├── examenes
├── parcial
├── practicos
│   ├── p0
│   │    ├── data
│   │    └── p0.ipynb
│   ├── p1
│   │   ├── data
│   │   └── p1.ipynb
│   ├── p2
│   │    ├── data
│   │    ├── images
│   │    └── p2.ipynb
│   ├── p3
│   │   ├── data
│   │   ├── images
│   │   └── p3.ipynb
│   └── p4
│       ├── data
│       │
│       └── p4.ipynb
├── proyecto_final
└── teoricos
    ├── 01 Introducción.pdf
    ├── 02 Datos.pdf
    ├── 03 operaciones-con-tablas.zip
    ├── 04 Análisis Exploratorio.pdf
    ├── 05 Análisis Exploratorio.pdf
    ├── 06 Feature Engineering.pdf
    ├── 07 Pruebas Estadísticas  Correlaciones.pdf
    ├── 08 Visualización de Datos.pdf
    ├── 09 Visualización de Datos.pdf
    ├── 10 Visualización de Datos.pdf
    ├── 11 Regresión Lineal.pdf
    ├── 12 Regresión Lineal.pdf
    ├── 13 Modelos de Clasificación.pdf
    ├── 14 Series de Tiempo.pdf
    ├── 15 Unsupervised Learning.pdf
    ├── 16 NLP overview.pdf
    ├── 17 Storytelling.pdf
    └── 18 Validation.pdf
```
 
### <a class='anchor' id='syllabus'></a><h1 style="text-align: center; background-color:powderblue; font-size:20px;">Syllabus 📚</h1>
<div style="background-color:#ECFFFF">

A continuación encontrará, tema por tema, una breve descripción de las clases teóricas junto con un listado de tópicos que se cubrirán en la misma.

<b>Nota:</b> Tanto el listado de temas como los tópicos que se presentan no son ni cercanamente exhaustivos. Tanto las clases como sus temáticas estan sujetas a cambio para mantener el curso actualizado.

<a class='anchor' id='introduccion'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Introducción 🏁</h1>

Esta clase es de carácter introductorio. En esta clase usted verá:
- Una visión general del curso.
- Métodos de evaluación y la estructura del curso.
- Breve introducción a las distintas áreas que conforman la Inteligencia Artificial (Data Science, Machine Learning, Deep Learning, Big Data, etc).
- Casos de uso y aplicaciones de Data Science.
- Qué es un data scientist? Diferencias con otras profesiones.
- Data Science Workflow.

<a class='anchor' id='datos'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Datos 💾</h1>

Esta clase provee información acerca de los tipos existentes de datos, su clasificación y problemas comunes con su uso. En esta clase usted verá:
- Cuales son los principales tipos de datos (estructurados, semi-estructurados, no estructurados).
- Clasificación de datos tabulares (categóricos/númericos).
- Limpieza de datos.
- Outliers.
- Datos faltantes.

<a class='anchor' id='operaciones_tablas'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Operaciones con tablas 📋</h1>

Esta clase consta de dos partes:
1. Una breve introducción que pretende cubrir de manera general los conceptos básicos que conforman el diseño de una base de datos.
2. Una parte teórico-práctica (hands-on) donde se le introducirá al lenguaje de programación SQL, viendo numerosas operaciones con tablas utilizando una pequeña base de datos.


<a class='anchor' id='eda_1'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Análisis exploratorio I 🧐</h1>

Esta clase a usted se le introducirá al análisis exploratorio de datos, un proceso crítico que pretende realizar investigaciones iniciales sobre los datos para descubrir patrones, detectar anomalías, probar hipótesis y verificar suposiciones con la ayuda de estadísticas resumidas y representaciones gráficas. En esta sección, que consta de dos partes, no se hará enfasis en el análisis exploratorio gráfico ya que se más adelante esto se cubrirá en la sección de visualización.

En esta sección usted verá:
- Conceptos básicos de distribuciones estadísticas (media, moda, mediana, desviación estándar, varianza, etc).
- Distribuciones estadísticas (normal, skewed, bimodal, etc).
- Asimetría, sesgo, Kurtosis, etc. 

<a class='anchor' id='eda_2'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Análisis exploratorio II 🧐🧐</h1>

Continuación de la clase anterior. Verá nuevos conceptos como:
- Población vs. Muestra.
- Sampling.
- Intervalos de confianza.
- Pruebas de hipótesis.
- p-value.
- Test estadísticos (Z-test, ANOVA, chi-cuadrado, etc).

<a class='anchor' id='feature_engineering'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Feature engineering 👷🏼‍♂️</h1>

La ingeniería de atributos (feature engineering) se refiere al proceso de utilizar el conocimiento del dominio para seleccionar y transformar las variables más relevantes a partir de datos sin procesar. En esta clase usted verá métodos de feature engineering tales como:
- Encoders: Ordinal encoding, Label encoding, One Hot encoding, etc.
- PCA y la maldición de la dimensionalidad.
- Normalización y estandarización.
- Remoción y manejo de outliers.
- Métodos de discretización supervisados y no supervisados.
- Imputación de valores faltantes.


<a class='anchor' id='visualizacion_1'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Pruebas estadísticas 🧮</h1>

En esta clase usted profundizará sus conocimientos de estadística, usted verá:
- Correlaciones: Pearson, Spearman, espúrea, etc.
- t-test, two sample t-test.
- z-test, two sample z-test.
- ANOVA.
- Probabilidad.
- Test chi-cuadrado.


<a class='anchor' id='visualizacion_1'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Visualización de datos I 📈</h1>

La visualización de datos es la práctica de traducir información a un contexto visual, como un mapa o un gráfico, para que el cerebro humano pueda comprender los datos y extraer información de ellos con mayor facilidad. Esta clase es la primer clase de una serie de clases sobre visualización, usted verá:
- Importancia, características y herramientas de visualización.
- Gráficas como: single number, icon array, donut graph, pie chart, bar chart, visualización de intervalos de confianza, slope graph, back-to-back bars, dumbell plots, dot plots, small multiples, etc.  

<a class='anchor' id='visualizacion_2'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Visualización de datos II  📉</h1>

Esta clase es la segunda clase de una serie de clases sobre visualización, usted verá:
- Objetivos y relevancia de la visualización.
- Gráficas como: benchmark line, combo chart, bullet graph, indicator dots, stacked bars, diverging stack bars, aggregated stack bar, rating column graph, lollipop variation, histogram, tree map, geographical maps.

<a class='anchor' id='visualizacion_3'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Visualización de datos III 📊</h1>

Esta clase es la tercer clase de una serie de clases sobre visualización, usted verá:
- Tipos de audiencia y qué clase de historias podemos contar
- Gráficas como: scatterplots, diagramas, word clouds, heatmap, line graph, area graph, stacked columns, deviation bar, sankey diagram.
- Anti-ejemplos de visualizaciones.

<a class='anchor' id='regresion'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Regresión Lineal  🔢</h1>

La regresión es una técnica de aprendizaje automático supervisado que se utiliza para predecir valores continuos. En esta clase se pretende introducirlo al algoritmo más sencillo de esta rama: la regresión lineal. En esta clase usted verá:
- Regresión lineal simple.
- Como entrenar un algoritmo y hacer predicciones.
- Interpretación de los coeficientes.
- R-cuadrado.
- Cómo se realiza el ajuste de parámetros internos del algoritmo.
- Supuestos, ventajas y desventajas.

<a class='anchor' id='clasificacion'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Modelos de clasificación 🌳</h1>

La clasificación es un tarea de aprendizaje automático supervisado que se enfoca en categorizar datos en clases o categorías. En esta clase se pretende introducirlo a este problema introduciendo algoritmos sencillos como regresión logística, árboles de decisión y K-nearest neighbours. En esta clase usted verá:
- Conceptos básicos asociados a problemas de clasificación como entropía y ganancia de información.
- K-nearest neighbours.
- Árboles de decisión.
- Regresión logística.

<a class='anchor' id='series_tiempo'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Series de tiempo ⏳</h1>

El análisis de series de tiempo comprende los métodos para analizar datos de series temporales con el fin de extraer estadísticas significativas y generar predicciones. En esta clase usted verá:
- Conceptos básicos como: estacionalidad, tendencia, cambios cíclicos, cambios irregulares.
- Modelos como: zero mean, random walk, seasonality models, trend models.
- Concepto de estacionariedad.
- Modelos más avanzados como: moving average, auto-regressive models, ARIMA, etc.

<a class='anchor' id='unsupervised'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Aprendizaje no supervisado  🁋</h1>

El aprendizaje no supervisado es un tipo de problema de machine learning donde se pretende aprender patrones a partir de datos no etiquetados y agrupar los datos en conjuntos con características similares. En esta clase usted verá:
- Conceptos básicos de clustering.
- Algoritmos de clustering como: hierarchical clustering, K-Means, DBSCAN, etc.
- Mecanismos de evaluación de clustering.
- Problemas asociados.

<a class='anchor' id='nlp'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Procesamiento de Lenguaje Natural  📘📗📕</h1>

El procesamiento del lenguaje natural es un subcampo de la lingüística, la informática y la inteligencia artificial que se ocupa de las interacciones entre las computadoras y el lenguaje humano, en particular, cómo programar las computadoras para procesar y analizar grandes cantidades de datos del lenguaje natural. En esta clase usted verá:
- Problemas clásicos.
- Mecanismos de pre-procesamiento de textos como: tokenización, remoción de palabras cortas, stemming, lematización, etc.
- Bag of words, n-gramas, TF-IDF.
- Vector space models.
- Latent Dirichlet allocation.

<a class='anchor' id='validacion'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Validación 🎯</h1>

La validación del modelo es el proceso fundamental para estimar el rendimiento de generalización de un model predictivo, aumentar el rendimiento predictivo, identificar el algoritmo de aprendizaje y sus híper-parámetros. En esta clase usted verá:
- Conceptos generales relacionados a la validación de modelos.
- Desbalance de clases y estratificación.
- Holdout validation.
- Three way holdout validation.
- Ajuste de híper-parámetros.
- Cross-validation.


<a class='anchor' id='storytelling'></a><h1 style="text-align: center; background-color:#C9F3F3; font-size:15px;">Storytelling 💬</h1>

La narración es la actividad social y cultural de compartir historias, a veces con improvisación, teatro o adornos. En esta clase usted verá:
- Definición, características e importancia de la comunicación de resultados.
- Cómo formular y estructurar historias utilizando diversas herramientas.
- Técnicas de un proceso narrativo.

</div> 