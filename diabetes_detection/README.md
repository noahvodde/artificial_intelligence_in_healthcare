![Banner](attachments/diabetes_banner.png)
![Python version](https://img.shields.io/badge/Python-3.9-blue)
![NumPy version](https://img.shields.io/badge/NumPy-1.24-blue)
![Pandas version](https://img.shields.io/badge/Pandas-1.5-blue)
![Matplotlib version](https://img.shields.io/badge/Matplotlib-3.6-blue)
![Seaborn version](https://img.shields.io/badge/Seaborn-0.12-blue)
![Scikit-Learn version](https://img.shields.io/badge/ScikitLearn-1.2-blue)
![TensorFlow version](https://img.shields.io/badge/TensorFlow-2.10-blue)
![Mlxtend version](https://img.shields.io/badge/Mlxtend-0.21-blue)
![License](https://img.shields.io/badge/License-MIT-blue)
# Diabetes Detection
## Author
- [@novotz](https://github.com/novotz)

## Table of contents
- [Project description](#1)
- [Data source](#2)
- [Results](#3)
- [Explore the notebook](#4)
- [Repository structure](#5)

<a id='1'></a>
## Project description
Diabetes is a chronic disease associated with elevated blood glucose levels in the
body. Diabetes often leads to cardiovascular disease, stroke, kidney damage and 
long-term damage to the extremities (i.e. limbs and eyes). One of the barriers to 
early detection and diagnosis of diabetes is that the early stages of diabetes 
often have no symptoms. People who are on the path to diabetes (pre-diabetes) 
often do not know they have diabetes until it is too late. In this project, we 
will use deep learning to solve this problem. For this purpose, we create a 
neural network with Keras that is trained on the basis of data in order to be 
able to recognise diabetes later. In this context, not only the creation but 
also important data techniques (handling missing values, outlier detection, etc.)
will be explained in the notebook. 

<a id='2'></a>
## Data Source
The [data](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
we will use for this project is from the Pima Indian Diabetes dataset.
This consists of diagnostic measurements collected from a sample of Pima Indian 
females, along with a label indicating whether the patient developed diabetes 
within five years of the first measurement.

<a id='3'></a>
## Results
Overall, we are able to predict with our neural network whether a new patient will
develop diabetes within the next five years with an accuracy of **~89%** based on 
the eight readings of that patient.

<a id='4'></a>
## Explore the notebook
Click [here](notebook/diabetes_detection.ipynb) for more detailed information about this project.

<a id='5'></a>
## Repository structure
```
📦diabetes_detection
 ┣ 📂attachments
 ┃ ┗ 📜diabetes_banner.png
 ┣ 📂data
 ┃ ┗ 📜diabetes.csv
 ┣ 📂notebook
 ┃ ┣ 📂diabetes_detection_model
 ┃ ┃ ┣ 📂assets
 ┃ ┃ ┣ 📂variables
 ┃ ┃ ┃ ┣ 📜variables.data-00000-of-00001
 ┃ ┃ ┃ ┗ 📜variables.index
 ┃ ┃ ┣ 📜keras_metadata.pb
 ┃ ┃ ┗ 📜saved_model.pb
 ┃ ┗ 📜diabetes_detection.ipynb
 ┣ 📂pictures
 ┃ ┗ 📜diabetes_detection_flowchart.png
 ┣ 📜README.md
 ┗ 📜requirements.txt
```
