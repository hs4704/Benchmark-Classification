# Benchmark Classification Models for Diabetes and Hypothyroid Prediction
This project explores the application of machine learning classification models to predict two medical conditions: diabetes and hypothyroidism. Using Python and its libraries, various algorithms were implemented, evaluated, and compared to determine their performance on these datasets.

# Project Overview
- Analyzed the datasets for diabetes and hypothyroidism prediction.
- Built and evaluated classification models, including:
	- Logistic Regression
  	- K Nearest Neighbors (KNN)
  	- Decision TreeNaive Bayes
  	- Linear Discriminant Analysis (LDA)
  	- Support Vector Machine (SVM)
- Compared the models’ performance using metrics such as accuracy, precision, recall, F1-score, and mean squared error.
# Datasets
1. Diabetes Dataset: A dataset containing features related to diagnosing diabetes.
- Source: https://www.kaggle.com/datasets/mathchi/diabetes-data-set
2. Hypothyroid Dataset: A dataset with features for diagnosing hypothyroidism.
- Source: https://www.kaggle.com/datasets/yasserhessein/thyroid-disease-data-set
# Results
The models were evaluated on their ability to accurately classify the conditions. Key findings included:

## Diabetes
<img width="500" height="400" alt="DIABETES Precision" src="https://github.com/user-attachments/assets/2410d9af-da2f-424c-9f63-845809bc88dc" />
<img width="500" height="400" alt="Unknown" src="https://github.com/user-attachments/assets/79f4b8bb-87cf-4eac-8709-5d48571fabaa" />

- KNN and Decision Trees performed strongly for diabetes prediction, with high accuracy and balanced precision-recall values.

## Hypothyroidism
<img width="500" height="400" alt="HYPOTHYROID PRECISION" src="https://github.com/user-attachments/assets/19b589c2-bfed-4804-a532-b677c3e46391" />

<img width="500" height="300" alt="HYPOTHYROID ROC" src="https://github.com/user-attachments/assets/40b8bf6f-b57a-412e-a4c9-b2c23e16a37d" />

- KNN achieved the best balance of precision and recall, while Naive Bayes showed high recall but lower precision.
# Features of the Repository
- **Python Notebooks**: The notebooks contain all of the preprocessing steps, model training, evaluation and visualizations
- **Datasets**: The diabetes and hypothyroidism datasets are located in the 'data' file, we used these for training and evaluation.
## Lessons Learned 
Through this project, I enhanced my understanding and ability to:
- Preprocess and clean large medical datasets.
- Implement various classification algorithms in Python.
- Compare and interpret model performance metrics.
- Understand the importance of model selection and evalustion for specific datasets.
  
