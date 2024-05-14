# Chest X-ray Image Classification Project

## Introduction and Background Information

Chest X-ray imaging plays a crucial role in medical diagnostics, aiding in the detection and monitoring of various thoracic pathologies. However, its efficacy can be limited due to challenges in image interpretation and the two-dimensional nature of X-ray images. As a result, complementary imaging techniques such as CT or MRI may be required for a comprehensive diagnosis. This project aims to explore the effectiveness of traditional machine learning methods and neural network architectures in overcoming the limitations of X-ray imaging and accurately distinguishing various chest diseases.

## Problem Description

The main question addressed in this project is: "To what extent do traditional learning methods and neural network architectures be effective in overcoming the limitations of X-ray imaging and distinguishing the various chest diseases?" This question leads to several sub-questions related to data preprocessing, comparison of methods, and the ability to differentiate diseases. The project focuses on classifying chest X-ray images into different disease categories or identifying images with no indication of disease.


## Dataset (DS)

The dataset used contains over 112,000 Chest X-ray images from more than 30,000 unique patients. The images are multi-labeled with information regarding the presence of 14 common thoracic pathologies. For this project, subsets of the dataset were created focusing on specific disease categories, such as atelectasis, effusion, nodule, pneumothorax, and "no finding". Three different subsampled datasets (DS-1, DS-2, DS-3) were utilized for experimentation.

### DS-1
- Randomly subsampled 9000 images
- Imbalanced dataset

### DS-2
- Subsampled DS-1 to create a balanced dataset
- Removed infiltration instances
- Ensured image sizes and view positions match

### DS-3
- Contains 1000 images in total, 200 images per finding
- Focuses on atelectasis, effusion, nodule, pneumothorax, and "no finding"

## Methods

### Traditional Methods
- Naive Bayes Classifier
- Random Forest Classifier
- AdaBoost Classifier
- KNN Classifier
- Decision Tree
- Support Vector Machine
- Logistic Regression

### Neural Network Methods
- Custom CNN Models
- MobileNet
- ResNet
- VGG19
- GoogLeNet (Inception)
- DenseNet121

## Results & Discussions

The project evaluates the performance of traditional methods and neural network architectures in classifying chest X-ray images. Results and discussions are provided for each method and dataset, highlighting the effectiveness and limitations of different approaches.

## Conclusions

The project concludes by summarizing the findings and insights gained from the experimentation. It discusses the potential of traditional methods and neural network architectures in improving the accuracy of chest X-ray image classification and suggests future research directions.

