# Cancer_Cell_Classification-SVM

## Introduction
This project aims to classify cancer cells as malignant or benign using a Support Vector Machine (SVM) classifier. The goal is to build a reliable model to assist in early diagnosis and treatment planning based on cell features.  

## About the Dataset
The dataset used in this project contains various features of cell samples, which include measurements such as cell radius, clump_thickness, size_uniformity,	shape_uniformity and other relevant factors. The target variable indicates whether the cell is malignant or benign.  

## Tools and Libraries
- **Python**: Programming language used for data processing and model building.  
- **Pandas**: For data manipulation and analysis.  
- **NumPy**: For numerical operations.  
- **Scikit-learn**: For building and evaluating the SVM model.  
- **Jupyter Notebook**: For interactive data analysis and model training.  

## Steps
1. **Data Loading and Preprocessing**:  
   - Load the dataset from a CSV file.  
   - Handle missing values and encode categorical features.  
   - Split the dataset into training and testing sets.  
   - Standardize the features.  

2. **Model Training**:  
   - Train an SVM classifier using the training data.  

3. **Model Evaluation**:  
   - Evaluate the model on the test data using accuracy, precision, recall, and F1-score.  
   - Generate a confusion matrix to visualize the performance.  

## Outcome
The project successfully trains an SVM classifier to distinguish between malignant and benign cancer cells with high accuracy. The model's performance is evaluated using various metrics to ensure its reliability.  

## Conclusion
The SVM classifier demonstrated robust performance in classifying cancer cells based on the given features. This model can be further refined and validated with additional data and techniques to improve its accuracy and generalizability.  

## Metrics
- **Accuracy**: 98%  
- **Precision**: 98%  

