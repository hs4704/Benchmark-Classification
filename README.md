# 🧬 Benchmark Classification Models for Diabetes and Hypothyroid Prediction
This project applies and compares machine learning classification models to predict two medical conditions: **diabetes** and **hypothyroidism**. Using Python and scikit-learn, multiple algorithms were evaluated to determine the most effective model for each condition based on clinical datasets.

---

## 🧠 Project Summary
Early diagnosis of chronic conditions like diabetes and hypothyroidism is critical for patient outcomes. This project benchmarks several supervised classification models to identify which algorithms provide the best performance in real-world medical datasets. Evaluation focused on accuracy, precision, recall, F1-score, and ROC-AUC.

---

## 🔬 Objectives

- Apply multiple classification algorithms to medical diagnostic datasets.
- Evaluate and compare model performance across key metrics.
- Understand how model selection impacts predictive reliability in healthcare.

---

## 📊 Algorithms Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Naive Bayes  
- Linear Discriminant Analysis (LDA)  
- Support Vector Machine (SVM)

---
## 🗂️ Project Structure

```
Medical-Classification-Benchmark/
├── data/              # Datasets for diabetes and hypothyroid prediction
├── notebooks/         # Jupyter notebooks for each stage of the analysis
├── results/           # Charts and visual outputs (e.g., confusion matrices, ROC curves)
├── README.md          # Project documentation
```
---

## Datasets
1. Diabetes Dataset: A dataset containing features related to diagnosing diabetes.
- Source: https://www.kaggle.com/datasets/mathchi/diabetes-data-set
2. Hypothyroid Dataset: A dataset with features for diagnosing hypothyroidism.
- Source: https://www.kaggle.com/datasets/yasserhessein/thyroid-disease-data-set

---
## 📈 Results Summary

### 🔹 Diabetes Prediction

![Diabetes Precision](https://github.com/user-attachments/assets/2410d9af-da2f-424c-9f63-845809bc88dc)
![Diabetes ROC](https://github.com/user-attachments/assets/79f4b8bb-87cf-4eac-8709-5d48571fabaa)

- **KNN** and **Decision Tree** achieved the highest accuracy with strong precision-recall balance.
- **SVM** also performed well, especially in minimizing false negatives.

---
### 🔹 Hypothyroid Prediction

![Hypothyroid Precision](https://github.com/user-attachments/assets/19b589c2-bfed-4804-a532-b677c3e46391)
![Hypothyroid ROC](https://github.com/user-attachments/assets/40b8bf6f-b57a-412e-a4c9-b2c23e16a37d)

- **KNN** showed the best overall balance of precision and recall.
- **Naive Bayes** yielded high recall but lower precision — useful in certain high-risk screening scenarios.

---
## 📌 Key Takeaways

- Preprocessing and feature scaling significantly influenced model performance.
- No single model is universally superior — performance depends on the problem and data.
- Model interpretability is key in medical contexts, especially where false positives/negatives have serious consequences.

---
## 🧪 Lessons Learned

- Improved understanding of supervised ML pipelines using scikit-learn.
- Gained hands-on experience evaluating models using multiple statistical metrics.
- Developed fluency in applying ML techniques to healthcare problems.

---

## 🧰 Tools Used

- Python (Jupyter Notebooks)  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Kaggle Datasets

---


  
