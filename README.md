# Kyphosis Disease Classification

## Project Overview
This project focuses on the development and implementation of a classification model to predict the presence or absence of kyphosis, an abnormally excessive convex curvature of the spine, in children who have undergone corrective spinal surgery. The model utilizes Decision Trees and Random Forest Classifier algorithms to analyze data related to the patients' age, the number of vertebrae involved, and the number of the first vertebra operated on.

## Data
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/abbasit/kyphosis-dataset) and contains 81 rows and 4 columns. The dataset includes the following features:

#### Inputs:
- Age: Age of the child in months.
- Number: The number of vertebrae involved.
- Start: The number of the first (topmost) vertebra operated on.
#### Output:
- Kyphosis: A categorical factor with levels "absent" or "present," indicating whether kyphosis was present after the operation.

## Model
The classification model is built using Decision Trees and Random Forest Classifier algorithms. These models are trained on the provided dataset to learn the patterns and relationships between the input features and the presence or absence of kyphosis. Decision Trees offer transparency in understanding the decision-making process, while Random Forest Classifier enhances the model's robustness by aggregating multiple decision trees.

## Results
The model's performance metrics, such as accuracy, precision, recall, and F1 score, are evaluated on a test set to assess its effectiveness in predicting kyphosis.
