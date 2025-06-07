# Hi there! I'm Luis Guillermo! :bowtie:

I have a bachelor's degree in Mathematics from Benemérita Universidad Autónoma de Puebla (BUAP) and a master's degree in Computer Science from Centro de Investigación en Ciencias y Estudios Superiores de Ensenada, Baja California (CICESE). Over the past two years, I’ve been learning about Machine Learning, Deep Learning, Data Science, and Data Analysis. In this repository, you’ll find some of my practices and experiments related to these topics, including those I worked on during my postgraduate studies.

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisgrl/) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

* Bachelor’s Thesis in Mathematics available in [BUAP’s Institutional Repository](https://repositorioinstitucional.buap.mx/items/2e1a95c6-75ef-4637-95e3-2fdc735030c8). :mortar_board:

## Main Projects/Practices

### Data Analysis :bar_chart: :chart_with_upwards_trend:

Data analysis begins with data collection and continues through exploration, cleaning, preprocessing, transformations, and more (Exploratory Data Analysis – EDA). The goal is to use the data either to gain meaningful insights or to support decision-making (Data-Driven). This process can even contribute to the development of artificial intelligence models.

* [Challenges IA Center-BOSCH](https://github.com/LuisGuillermoRL/Challenges_IA_Center) :star:
![img3_ch_f](https://github.com/user-attachments/assets/1456e066-0207-4e61-989d-6df4846fd3e2)

* [Exploratory Analysis (EDA) of the CBIS-DDSM Database](https://github.com/LuisGuillermoRL/EDA_CBIS-DDSM/tree/main) :chart:
<img width="611" alt="análisis" src="https://github.com/user-attachments/assets/c173ff31-7ac2-46d7-a433-e2c916b9fd7f" />

 ### Data Science :computer:

The role of a data scientist is more technical and it requires proficiency in programming languages, advanced technological tools, and mathematical knowledge such as statistics and linear algebra. These skills enable data scientists to design and implement models capable of extracting value from data to predict future outcomes or uncover hidden relationships within the data.

* [Exercises completed as part of the Ciencia de Datos para Sensores Inteligentes (CDSI) course](https://github.com/LuisGuillermoRL/Practicas_CDSI) :id:
* ![pract2_img1](https://github.com/user-attachments/assets/f999b02a-8d05-4745-816c-463cb697df91)

* [ML practices designed by Bosch - IA Center con BOSCH](https://github.com/LuisGuillermoRL/Challenges_IA-Center-ML) :star2:
* ![pract1](https://github.com/user-attachments/assets/be955cc3-489b-4fcd-864b-3af4a535be3f)

### Documents Related to the Master’s Thesis: Classification of Abnormalities in Mammograms Using Ensembles (a combination of ML and DL)
**Abstract:** Breast cancer is the most common cancer among women and one of the leading causes of morbidity and mortality, making it a global health concern. Mammography is a highly standardized imaging diagnostic technique used in early breast cancer detection programs. However, the visual assessment of breast density, classification of calcifications and masses (abnormality classification), both benign and malignant (pathologies), remains challenging due to the adipose tissue in the breasts. To address this issue, various approaches have been developed using machine learning.

* Master's Thesis available in [CICESE Institutional Repository](https://biblioteca.cicese.mx/catalogo/tesis/ficha.php?id=26756) :mortar_board:
* I submitted a [poster](https://github.com/LuisGuillermoRL/Docs_escritos/blob/main/poster_R.pdf) :pushpin: and wrote a [paper](https://github.com/LuisGuillermoRL/Docs_escritos/blob/main/131371H.pdf) related to the **Classification of breast cancer abnormalities (Masses vs. Calcifications)** to **SPIE (Society of Photo-Optical Instrumentation Engineers)**, which took place from August 18–22, 2024. Although this experiment does not aim to detect cancer, it was useful for evaluating the performance of various CNNs and exploring the combination of Machine Learning with Deep Learning. Soft voting was also applied using the CNNs involved (see Figure 7 and Table 5). <img width="563" alt="Voting_spie" src="https://github.com/user-attachments/assets/37693a57-6da5-43a1-82cd-67bffd0362f2" />

### Source Code of the Experiments from the Master's Thesis 🤖 

This study exclusively used the **CBIS-DDSM database** to conduct experiments focused on abnormality classification and early detection of breast cancer, the latter being the most significant. The study proposed combining machine learning methods with deep learning techniques to improve the classification performance compared to individually trained models. The approaches explored included *Transfer Learning*, *Fine-Tuning*, the use of *Convolutional Neural Networks (CNNs)* as both feature extractors and final classifiers, *Ensemble methods*, and the development of *Hybrid models*.

The experimentation was divided into three main blocks:

* **[BLOCK 1](https://github.com/LuisGuillermoRL/Distintos_Experimentos/tree/main)**. In this phase, several experiments were conducted using six CNNs: **VGG19, VGG16, ResNet50, MobileNetV2, InceptionV3**, and **DenseNet121**. The images used included both masses and calcifications, but the way they were grouped resulted in different experiments aimed at addressing the problem of early breast cancer detection. Below is an image illustrating the supervised training behavior of a convolutional neural network (**InceptionV3 model**) using a validation set in the **task of cancer classification with mass images**.
<img width="737" alt="inceptionv3" src="https://github.com/user-attachments/assets/bfa44bab-186c-4ffb-bdf7-255fe36225a3" />

Below is an image showing the monitored training behavior of a convolutional neural network (**ResNet50 model**) using a validation set for the **task of abnormality classification (Masses vs. Calcifications)**.
<img width="735" alt="Resnet" src="https://github.com/user-attachments/assets/e4eebd2d-3f11-47e7-b385-b936c7629cf4" />


:wrench: :nut_and_bolt: :hammer: :soon: 	:arrow_heading_down:

* **BLOCK 2**. In this section, nine CNNs were used: the six mentioned in **Block 1**, plus **ResNet50V2, ResNet101V2**, and **ResNet152V2**. It is worth noting that the images used included both masses and calcifications, but they were grouped in a way that allowed us to observe whether the inclusion of calcifications contributed to improving the early breast cancer classification rate.

* **BLOCK 3**. In the final part, only images corresponding to masses were used, and the focus was on exploring hybrid models to increase the early breast cancer classification rate. Below is an example of a hybrid model (an **Ensemble** of ResNet50V2, ResNet101V2, and ResNet152V2 models).![Ensamble](https://github.com/user-attachments/assets/ad6982fd-f19f-49fc-be95-e56979d741de)

### :wrench: :nut_and_bolt: :hammer: Bayesian Network (BN) :wrench: :nut_and_bolt: :hammer: :soon:

A Bayesian Network (BN) is a probabilistic graphical model that represents a set of variables and their conditional dependencies through a directed acyclic graph (DAG). It is based on Bayes' Theorem and allows for making inferences from data, provided a DAG structure and relevant data are available. During my postgraduate studies, I built a Bayesian Network capable of **predicting employee attrition** based on specific data and a proposed DAG. Key characteristics:
- Each node has a Conditional Probability Table (CPT) that describes how it depends on its parent nodes in the graph.
- Based on Bayes’ Theorem, it allows updating probabilities as new information becomes available.
- Given a set of observations, it can calculate probabilities for other unknown variables.
  
[Report_Bayesian_Network.pdf](https://github.com/user-attachments/files/18778520/Reporte_Red_Bayesiana.pdf)

