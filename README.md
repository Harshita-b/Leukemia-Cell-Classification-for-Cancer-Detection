# Leukemia-Cell-Classification-for-Cancer-Detection
![Image Alt Text](https://medlineplus.gov/images/LeukemiaWBC_share.jpg)
### Overview
Welcome to the Leukemic Cell Classification Project! This project aims to develop a robust and highly accurate machine learning model for classifying leukemic cells from microscopic images. By harnessing the power of various machine learning algorithms, including Random Forest, K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Convolutional Neural Networks (CNN), and Naive Bayes, we strive to create an automated system that can distinguish between normal and leukemic cells. The successful implementation of this project has the potential to revolutionize clinical decision-making, enhance diagnostic accuracy, and improve treatment outcomes for leukemia patients, particularly within the pediatric population.

### Dataset
Our dataset comprises a comprehensive collection of 15,135 segmented cell images obtained from 118 patients. Each image has undergone meticulous annotation by expert oncologists, providing valuable ground truth labels for training and evaluation. The dataset accurately reflects real-world scenarios, encompassing staining noise and illumination errors often encountered in microscopic imaging. Rigorous efforts have been made to rectify these errors during the image acquisition process to ensure dataset reliability and quality.

### Dataset Features:

Image Format: .bmp
Color Encoding: 8-bit RGB
Data Splits: Train, Test, Validation
Training Folds: fold_0, fold_1, fold_2
Folders: all (images with leukemia cells), hem (images without cells or leukemia)
### Methodology
Feature Extraction and Preprocessing
Prior to classification, the dataset undergoes preprocessing to enhance image quality and extract crucial features. Attributes like cell shape, texture, and spatial connections are extracted to capture the properties of leukemic cells. These features provide the foundation for the subsequent machine learning algorithms.

### Algorithms Utilized
- Random Forest
- K-Nearest Neighbors (KNN):
- Support Vector Machines (SVM)
- Naive Bayes
- Convolutional Neural Networks (CNN):

### Evaluation
The performance of each algorithm is assessed using appropriate metrics such as accuracy, precision, recall, and F1 score. Through rigorous testing and comparison, the Convolutional Neural Network (CNN) algorithm has demonstrated itself as the most suitable choice for this project, given its proficiency in medical picture analysis and classification tasks.

### Objective
The primary objective of this project is to create an automated and reliable system for leukemic cell classification. Accurate identification and classification of leukemic cells can aid in early detection and timely treatment of leukemia, potentially improving patient outcomes, particularly for children diagnosed with Acute Lymphoblastic Leukemia (ALL).

### Contribution
By enabling automated and reliable leukemia cell classification, this project aspires to make significant contributions to the field of medical image analysis. The outcomes have the potential to revolutionize clinical decision-making, enable personalized treatment approaches, and ultimately enhance the prognosis for leukemia patients.
