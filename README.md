# Diabetes Risk Classification
This project evaluates several supervised machine learning models for predicting diabetes risk using health and lifestyle data.
The dataset was obtained from Kaggle and simulates realistic patterns associated with diabetes development.

## Dataset
- Source: Kaggle
- Records: 6,000
- Attributes: 19
- Target Classes: 
    - Low Risk
    - Prediabetes
    - High Risk
The dataset contains a combination of numerical and categorical variables.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Machine Learning Models
The following models were implemented and evaluated:

- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)

## Results and Key Findings

| Model | Accuracy |
|------|--------|
| Decision Tree | 90% |
| KNN | 90% |
| Naive Bayes | 84% |
| SVM | 94% |
| ANN | 95% |

- ANN achieved the highest overall accuracy (95%).
- ANN and SVM performed strongly across all risk categories.
- Naive Bayes showed the weakest overall performance, particularly for the Prediabetes class.
- Prediabetes was the most difficult category for all models to classify.
- BMI, waist circumference, and fasting glucose level were consistently identified as the most important predictors of diabetes risk. 

## Project Files

- `diabetes_analysis.ipynb`  
  Contains the complete analysis, preprocessing, model training, evaluation metrics, and visualizations.

- `data/diabetes_risk_dataset.csv`  
  Dataset used for model training and evaluation.