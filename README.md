# Hola, soy Luis Guillermo! :bowtie:

Licenciado en Matemáticas por parte de la Benemérita Universidad Autónoma de Puebla (BUAP) y Maestro en Ciencias Computacionales por parte del Centro de Investigación en Ciencias y Estudios Superiores de Ensenada, Baja California (CICESE). Durante estos últimos 2 años he estado aprendiendo aprendizaje máquina (Machine Learning - ML), aprendizaje profundo (Deep Learning - DL) y Ciencia de Datos, por lo que aquí podrás encontrar algunas prácticas y experimentos relacionados con estos temas, incluídos los que realicé en mi posgrado y que me ayudaron a realizar mi tesis.

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisgrl/) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

* Tesis de Licenciatura en Matemáticas en el [Repositorio Institucional de la BUAP](https://repositorioinstitucional.buap.mx/items/2e1a95c6-75ef-4637-95e3-2fdc735030c8). :mortar_board:

## Proyectos/Prácticas Principales

### Análisis de datos (Data Analysis) :bar_chart: :chart_with_upwards_trend:
El análisis de datos es muy amplio, ya que esta inicia en la recolección de los datos, pasando por la exploración de estos (en inglés es Exploratory Data Analysis - EDA), limpieza, preprocesamiento, transformaciones, etc., con el fin de utilizarlos, ya sea para que ayuden a obtener una interpretación y comunicar los resultados con el fin de tomar decisiones (en inglés Data Driven) o bien para desarrollar algún modelo de inteligecia artificial. A continuación se muestran prácticas que se centran principalmente en estas técnicas.

* [Challenges IA-Center con BOSCH](https://github.com/LuisGuillermoRL/Challenges_IA_Center) :star:
![img3_ch_f](https://github.com/user-attachments/assets/1456e066-0207-4e61-989d-6df4846fd3e2)

* [Análisis Exploratorio (EDA) de la base de datos CBIS-DDSM](https://github.com/LuisGuillermoRL/EDA_CBIS-DDSM/tree/main) :chart:
<img width="611" alt="análisis" src="https://github.com/user-attachments/assets/c173ff31-7ac2-46d7-a433-e2c916b9fd7f" />

 ### Ciencia de datos (Data Science) :computer:
El rol de un científico de datos es más técnico y amplio que el de un analista de datos, ya que requiere el dominio de lenguajes de programación, herramientas tecnológicas avanzadas y conocimientos matemáticos como estadística y álgebra lineal. Estas habilidades le permiten diseñar e implementar modelos capaces de extraer valor de los datos para predecir el futuro o descubrir relaciones ocultas en los datos.

* [Materia de Ciencia de Datos para Sensores Inteligentes (CDSI)](https://github.com/LuisGuillermoRL/Practicas_CDSI) :id:
* ![pract2_img1](https://github.com/user-attachments/assets/f999b02a-8d05-4745-816c-463cb697df91)

* [Prácticas de ML de IA-Center con BOSCH](https://github.com/LuisGuillermoRL/Challenges_IA-Center-ML) :star2:
* ![pract1](https://github.com/user-attachments/assets/be955cc3-489b-4fcd-864b-3af4a535be3f)

### Documentos Relacionados con la Tesis de Maestría: *Clasificación de anormalidades en mastografías utilizando ensambles* (combinación de ML con DL)
**Abstract:** El cáncer de mama es el cáncer más común en las mujeres y una de las principales causas de morbilidad y mortalidad, lo que lo convierte en un problema de salud con importancia mundial. La mamografía es una técnica de diagnóstico por imágenes altamente estandarizado para los programas de detección temprana del cáncer de mama, sin embargo, al día de hoy, la estimación de la densidad mamaria, la clasificación de calcificaciones y masas (clasificación de anormalidades), tanto en benignas como malignas (patologías) con evaluación visual sigue siendo un desafío debido al tejido adiposo de las mamas, por lo que se han creado distintas maneras de abordar este problema utilizando aprendizaje máquina.

* Tesis de Maestría en el [Repositorio Institucional de CICESE](https://biblioteca.cicese.mx/catalogo/tesis/ficha.php?id=26756) :mortar_board:
* Envié un [póster](https://github.com/LuisGuillermoRL/Docs_escritos/blob/main/poster_R.pdf) :pushpin: y redacté un [paper](https://github.com/LuisGuillermoRL/Docs_escritos/blob/main/131371H.pdf)  relacionado con la **Clasificación de anormalidades (Masas vs Calcificaciones)** de cáncer de mama al **SPIE (Society of Photo-Optical Instrumentation Engineers)**, el cual se llevó a cabo en los días 18-22 de Agosto del 2024. Aunque este experimento no ayuda a detectar cáncer, este sirvió para evaluar el rendimiento de distintas CNNs así como la exploración en la combinación del Aprendizaje de Máquina con el Aprendizaje Profundo al utilizar distintas CNNs como extractores de características. También se realizaron votaciones (soft voting) por parte de las CNNs utilizadas (imagen siguiente).
<img width="563" alt="Voting_spie" src="https://github.com/user-attachments/assets/37693a57-6da5-43a1-82cd-67bffd0362f2" />

### Código de programación de los experimentos de la Tesis de Maestría 🤖 
En este estudio se empleó **exclusivamente la base de datos CBIS-DDSM** para realizar experimentos que
incluyen la clasificación de anormalidades y la detección temprana del cáncer de mama, siendo este último la más relevante. Para ello, se propuso el uso de métodos de **aprendizaje máquina** junto con **aprendizaje profundo** para mejorar la tasa de clasificación de modelos entrenados individualmente. Las técnicas exploradas fueron el **aprendizaje por transferencia (transfer learning ), el ajuste fino (fine tuning)**, el uso de **redes neuronales convolucionales (CNNs)** como extractores de características y como clasificador final, el uso de **métodos de ensamble** y la exploración de **modelos híbridos.**

La experimentación se dividió en 3 grandes bloques experimentales:

* **[BLOQUE 1](https://github.com/LuisGuillermoRL/Distintos_Experimentos/tree/main)**. En esta parte se realizaron diversos experimentos utilizando 6 CNNs: **VGG19, VGG16, ResNet50, MobileNetV2, InceptionV3 y DenseNet121**, con las cuales experimentó  **[Jaamour et al. (2023)](./docs/BCD_using_DL_Techniques.pdf)**. Las imágenes utilizadas fueron tanto las masas como calcificaciones, pero la forma en que se agruparon generó distintos experimentos para atacar el problema de detección temprana del cáncer de mamá. A continuación se muestra una imagen en la que se supervisa el correcto comportamiento comportamiento del entrenamiento de una red neuronal convolucional (**modelo InceptionV3**) utilizando un conjunto de validación en la tarea de clasificación de cáncer usando Masas.

<img width="737" alt="inceptionv3" src="https://github.com/user-attachments/assets/bfa44bab-186c-4ffb-bdf7-255fe36225a3" />

A continuación se muestra una imagen en la que se supervisa el correcto comportamiento del entrenamiento de una red neuronal convolucional (**modelo ResNet50**) utilizando un conjunto de validación en la tarea de **Clasificación de anormalidades (Masas vs Calcificaciones)**.

<img width="735" alt="Resnet" src="https://github.com/user-attachments/assets/e4eebd2d-3f11-47e7-b385-b936c7629cf4" />


:wrench: :nut_and_bolt: :hammer: :soon: 	:arrow_heading_down:

* **BLOQUE 2**. En esta parte se utilizaron 9 CNNs, las 6 mencionadas en el **Bloque 1** más los modelos **ResNet50V2, ResNet101V2 y el modelo ResNet152V2**. Cabe mencionar que las imágenes utilizadas fueron tanto las masas como calcificaciones, pero se agruparon de tal forma que permitieran observar si el uso de calcificaciones ayudaban a aumentar la tasa de clasificación temprana del cáncer de mama.

* **BLOQUE 3**. En esta última parte se utilizaron solo las imágenes correspondiente a las masas y se exploró el uso de modelos híbridos para aumentar la tasa de clasificación temprana del cáncer de mama, basándonos en el artículo de **AUTOR**. A continuación **se muestra un modelo híbrido (Ensamble de CNNs):** ![Ensamble](https://github.com/user-attachments/assets/ad6982fd-f19f-49fc-be95-e56979d741de)

### :wrench: :nut_and_bolt: :hammer: Red Bayesiana :wrench: :nut_and_bolt: :hammer: :soon:

Una Red Bayesiana (RB) es un modelo probabilístico gráfico que representa un conjunto de variables y sus dependencias condicionales mediante un grafo dirigido acíclico (DAG). Se basa en el Teorema de Bayes y permite crear inferencias sobre ciertos conjuntos de datos en tanto se tenga un DAG propuesto y los datos. Durante el posgrado pude construir una Red Bayesiana que fuera capaz de **predecir la deserción laboral** en base a ciertos datos y un DAG propuesto. Características:
- Cada nodo tiene una Distribución de Probabilidad Condicional (CPT - Conditional Probability Table) que describe cómo depende de sus padres en el grafo.
- Basado en el Teorema de Bayes permite actualizar las probabilidades a medida que se obtiene nueva información.
- Dado un conjunto de observaciones, se pueden calcular probabilidades para otras variables desconocidas.

[Reporte_Red_Bayesiana.pdf](https://github.com/user-attachments/files/18778520/Reporte_Red_Bayesiana.pdf)

