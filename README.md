# 🩺 Diabetes Prediction – Binary Classification

This project was developed as the *Semi Evaluation Project* during the *NTI Summer Training – Machine Learning Track*.

## 📌 Project Overview
The goal of this project is to build a *Binary Classification model* to predict whether a person is diabetic or not, based on medical and demographic features.  

This was part of my *summer internship at the National Telecommunication Institute (NTI)*, where we practiced applying machine learning techniques to real-world healthcare data.

## 🗂 Dataset
- *Source*: (https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset/data)  
- *Records*: 100,000 
- *Features*: 8 input features (e.g., pregnancies, glucose level, BMI, age) + 1 target (diabetes).  
- *Challenge: The dataset is **imbalanced* (more non-diabetic records than diabetic ones).  

## ⚙ Workflow
1. *Data Preprocessing*
   - Handling missing values (replacing zeros in certain medical features).  
   - Scaling numeric features.  
   - Encoding categorical values.  

2. *Dealing with Imbalance*
   - Applied *SMOTE (Synthetic Minority Over-sampling Technique)* to balance classes.  

3. *Modeling*
   - Tested Logistic Regression, Decision Tree, and Random Forest.  
   - *Random Forest* achieved the best performance.  

4. *Evaluation*
   - Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.  
   - Final accuracy: ~97% on the test set.  

## 👩‍💻 Tools & Libraries
- Python (Google Colab)  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn  

## 🙌 Acknowledgements
Special thanks to *Dr. Mohamed Awni*, our instructor and supervisor during the NTI Summer Training.  

This project was a team effort with:  
- Youssef Taha
- Mohamed Mahmoud

## 🚀 Notes
This is a *learning project* as part of my ML journey.  
It may not be perfect, but it reflects the progress I’ve made during the training.  

## 🔗 Resources
- (https://www.kaggle.com/code/mennaadel111/diabetesprediction)

---
