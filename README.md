# BreastCancerClassification
This is used to classify the stage of the breast cancer whether it is benign or marginal
# Breast Cancer Classification using Random Forest

This project implements a breast cancer classification model using the **Random Forest** algorithm to predict whether a tumor is **benign** or **malignant**. The model is trained on the **Wisconsin Breast Cancer Diagnostic (WBCD)** dataset, achieving **96% accuracy** and **97% precision**.

## Table of Contents
- [Project Description](#project-description)
- [Algorithm Selection](#algorithm-selection)
- [Data Input and Preprocessing](#data-input-and-preprocessing)
- [Training and Evaluation](#training-and-evaluation)
- [Prediction Process](#prediction-process)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Project Description
The goal of this project is to create a machine learning model that can classify breast tumors as **benign** or **malignant** using medical diagnostic data. By leveraging the **Random Forest** algorithm, the model performs high-accuracy classification with the ability to evaluate feature importance, making it useful for both prediction and understanding the factors that influence the diagnosis.

## Algorithm Selection
We chose the **Random Forest** algorithm due to its high accuracy, robustness, and ability to handle high-dimensional data. Random Forest is an ensemble learning method that combines multiple decision trees to provide reliable predictions and minimize overfitting.

## Data Input and Preprocessing
The model uses the **Wisconsin Breast Cancer Diagnostic (WBCD)** dataset, which includes features like radius, texture, and smoothness of cell nuclei. The dataset is preprocessed by handling missing values, normalizing the data, and splitting it into training and testing sets.

## Training and Evaluation
The model was trained using the **Random Forest Classifier** from **scikit-learn**. After training, the model achieved **96% accuracy** and **97% precision** on the testing dataset. We evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Prediction Process
Once trained, the model can predict whether a new tumor sample is benign or malignant by analyzing its features and aggregating the results from multiple decision trees in the Random Forest. This process ensures accurate and consistent predictions.

## Conclusion
This Random Forest-based classification model offers a reliable and efficient tool for early breast cancer detection. With an accuracy of 96% and precision of 97%, it can assist healthcare professionals in making faster and more informed decisions. The model can be integrated into a web application for real-time predictions, providing valuable support in the diagnostic process.

## Technologies Used
- **Python**
- **scikit-learn** (for machine learning algorithms)
- **pandas** (for data manipulation)
- **numpy** (for numerical operations)
- **matplotlib / seaborn** (for visualization)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-classification.git
   cd breast-cancer-classification
