# Heart Disease Prediction

This project predicts the likelihood of heart disease in patients using various machine learning classification models.  
The dataset includes patient health parameters such as age, sex, chest pain type, blood pressure, cholesterol level, and ECG results.

## Introduction
The goal of this project is to analyze patient data and develop predictive models to identify the presence of heart disease.  
We implemented multiple algorithms and compared their accuracy to find the most effective model.

## 📊 Dataset
The dataset contains patient health records with the following features:

| Feature      | Description |
|--------------|-------------|
| age          | Age of the patient |
| sex          | 1 = Male, 0 = Female |
| cp           | Chest pain type (1–4) |
| trestbps     | Resting blood pressure (mm Hg) |
| chol         | Serum cholesterol (mg/dl) |
| fbs          | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg      | Resting electrocardiographic results (0, 1, 2) |
| thalach      | Maximum heart rate achieved |
| exang        | Exercise induced angina (1 = yes; 0 = no) |
| oldpeak      | ST depression induced by exercise |
| slope        | Slope of the peak exercise ST segment |
| ca           | Number of major vessels (0–3) colored by fluoroscopy |
| thal         | 3 = normal; 6 = fixed defect; 7 = reversible defect |
| target       | 1 = Heart disease present; 0 = No heart disease |

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handle missing values
   - Remove duplicates
   - Feature selection
2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries
   - Visualizations (heatmaps, histograms, bar plots)
3. **Model Training**
   - Logistic Regression — **83.61%**
   - Naïve Bayes — **80.33%**
   - K-Nearest Neighbors — **65.57%**
   - Decision Tree — **85.25%**
   - Random Forest — **86.89%**
4. **Model Evaluation**
   - Accuracy score comparison
   - Best model: **Random Forest**

## 🛠️ Technologies Used
- **Python**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
## 📈 Results

| Model                 | Accuracy (%) |
|-----------------------|--------------|
| Logistic Regression   | 83.61        |
| Naïve Bayes           | 80.33        |
| K-Nearest Neighbors   | 65.57        |
| Decision Tree         | 85.25        |
| Random Forest         | **86.89**    |

✅ **Random Forest** performed the best for this dataset.


