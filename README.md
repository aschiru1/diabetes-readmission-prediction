# Predictive Analytics for Reducing Readmission Rates in Diabetic Patients  

## 📌 Project Overview  
Hospital readmissions can be costly and indicate suboptimal patient care. This project leverages predictive analytics to analyze factors influencing diabetes-related hospital readmissions and develop models to predict high-risk patients.  

## 📊 Dataset  
- Source: UCI Machine Learning Repository - Diabetes 130-US hospitals dataset  
- Data Features: Includes patient demographics, medical history, lab results, and hospital visit records  
- Target Variable: Whether a patient was readmitted within 30 days  

## 🛠️ Technologies Used  
- **Python**  
- **Pandas, NumPy** (Data Handling)  
- **Matplotlib, Seaborn** (Exploratory Data Analysis)  
- **Scikit-learn** (Machine Learning)
- **Scipy, Statsmodels**(Statistical Analysis) 

## 🚀 Steps in the Project  

### **1️⃣ Data Cleaning**  
- Replaced missing values (`?`) with NaN and handled missing data  
- Dropped irrelevant columns (`weight`, `payer_code`, `medical_specialty`)  
- Converted age ranges into numerical values  

### **2️⃣ Exploratory Data Analysis (EDA) & Statistical Analysis**  
- **Visualizations**: Distribution of age, race, and readmission rates
- **Statistical Tests**
- **T-tests & ANOVA**: Checking for differences in readmission rates across different groups  
- **Chi-Square Test**: Assessing relationships between categorical variables (e.g., medication usage and readmission)  
- **Correlation Analysis**: Identifying relationships between numerical features

### **3️⃣ Machine Learning Modeling**  
- Implemented models including:  
  - **Logistic Regression**  
  - **Random Forest Classifier**  
  - **K-Nearest Neighbours**
- Evaluated models using **accuracy, precision, recall, and F1-score**  

## 📌 Results & Findings  
- The best-performing model achieved **89% accuracy** in predicting readmission rates  
- **Feature Importance Analysis**: Key predictors included **insulin levels, prior hospital visits, and diagnosis codes**  
  Certain medications were associated with **higher or lower readmission rates**
  
