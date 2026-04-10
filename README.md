# 🧠 Thyroid Disease Detection using Machine Learning

## 📌 Project Overview
This project focuses on predicting thyroid cancer risk using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and classification models to detect whether a patient has **Benign** or **Malignant** thyroid conditions.

The dataset contains **212,000+ patient records**, making it a large-scale, real-world healthcare dataset.

---

## 🎯 Objectives
- Analyze thyroid patient dataset  
- Perform data cleaning and preprocessing  
- Explore relationships between medical features  
- Build classification models for disease prediction  
- Evaluate model performance using metrics  

---

## 📊 Dataset Description
The dataset includes the following features:

- 👤 Age  
- 🚻 Gender  
- 🧬 Family History  
- ☢️ Radiation Exposure  
- 🧂 Iodine Deficiency  
- 🚬 Smoking  
- ⚖️ Obesity  
- 🩺 Diabetes  
- 🧪 TSH, T3, T4 Levels  
- 📏 Nodule Size  
- 🎯 Diagnosis (Target: Benign / Malignant)  

---

## 🧹 Data Cleaning & Preprocessing
- Removed irrelevant columns (Country, Ethnicity)  
- Checked and confirmed no duplicate values  
- Converted categorical variables using **One-Hot Encoding**  
- Selected relevant features for modeling  

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Age Analysis
- Certain age groups show higher thyroid disease occurrence  

### 🔹 Gender Distribution
- Female patients appear more frequently in the dataset  

### 🔹 Smoking & Diabetes Impact
- Lifestyle factors influence thyroid diagnosis  

### 🔹 TSH Level Distribution
- Hormone levels show variation across patients  

---

## 🔗 Feature Engineering
- Selected important medical and lifestyle features  
- Applied encoding to convert categorical variables  
- Created structured dataset for ML models  

---

## 🔥 Correlation Analysis
- Weak correlations observed between most features  
- Indicates complex and non-linear relationships in medical data  

---

## 🤖 Machine Learning Models

### 🔹 Logistic Regression
- Baseline classification model  
- Simple and interpretable  

---

### 🔹 Decision Tree Classifier ⭐
- Captures non-linear relationships  
- Performs better on complex medical datasets  

---

## 📊 Model Evaluation Metrics
- Accuracy Score  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 📉 Key Insights
- Medical datasets are highly complex  
- Lifestyle and medical features both impact diagnosis  
- Decision Tree performs better than Logistic Regression  
- Reducing false negatives is critical in healthcare  

---

## 📌 Conclusion
This project demonstrates how machine learning can be applied to healthcare data for early detection of thyroid cancer risk. Decision Tree models outperform linear models by capturing complex patterns in the dataset.

---

## 🔮 Future Work
- Implement Random Forest and XGBoost  
- Perform hyperparameter tuning  
- Deploy as a web app using Streamlit  
- Integrate real-time patient data  

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📁 Project Structure

- Thyroid-Disease-Detection/
- │── thyroid_cancer_risk_data.csv
- │── thyroid_analysis.ipynb
- │── README.md

---

## 👤 Author
**Sheshu Vardhan**  
Aspiring Data Analyst | Machine Learning | Python  

---

## ⭐ Support
If you found this project helpful, consider giving it a ⭐ on GitHub!

---