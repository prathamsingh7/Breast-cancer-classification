# Problem statement
<p align="center">
  <img width="460" height="300" src="https://github.com/prathamsingh7/Breast-cancer-classification/blob/main/Images/breast-cancer-facts.jpg">
</p>

Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.
In this note book we will try to identify if the patient has IDC or not by using CNN.

# Objective of this project
- To implement a convolutional neural network (CNN) model for accurate IDC classification, by balancing the dataset and tuning hyperparameters.

- The proposed model achieves an accuracy of 99% for the classification of histopathological images, and outperforms the baseline CancerNet model with accuracy of 86%.

# Dataset
The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 30 x 30 were extracted (198,738 IDC negative and 78,786 IDC positive). Each patch’s file name is of the format: u_xX_yY_classC.png — > example 10253_idx5_x1351_y1101_class0.png . Where u is the patient ID (10253_idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.

The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images). 

<p align="center">
  <img width="460" height="300" src="https://github.com/prathamsingh7/Breast-cancer-classification/blob/main/Images/Dataset.png">
</p>

# Techstack Used

- ***Numpy***, ***Pandas*** for data pre-processing/manipulation.

- ***Matplot***, ***Seaborn*** and ***skimage*** for data visualization.

- ***Sklearn*** for ML model library and evaluation metrics.

- ***Tensorflow*** and ***keras*** for building CNN model.
