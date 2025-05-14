# 🧠 Diabetes Prediction Using Machine Learning

This project applies machine learning techniques to predict the likelihood of a person having diabetes based on diagnostic measurements. The dataset includes various medical predictor variables and one target variable indicating diabetes presence.

## 📁 Project Structure

```
.
├── diabetes-prediction.ipynb   # Jupyter Notebook with full analysis and modeling
├── README.md                   # Project overview and usage guide
```

## 📊 Dataset

- Source: https://www.kaggle.com/datasets/ziya07/diabetes-clinical-dataset100k-rows
- Features:
  year                 
  gender               
  age                  
  location              
  race:AfricanAmerican  
  race:Asian            
  race:Caucasian        
  race:Hispanic        
  race:Other           
  hypertension          
  heart_disease        
  smoking_history      
  bmi                  
  hbA1c_level          
  blood_glucose_level   
  diabetes               
  clinical_notes        
- Target:
  - Outcome (1 = diabetic, 0 = non-diabetic)

## ⚙️ Workflow Overview

The notebook includes the following steps:

1. **Data Preprocessing**
   - Handling missing values
   - Feature scaling
   - Correlation analysis

2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and relationships using seaborn and matplotlib

3. **Modeling**
   - Split into training and test datasets
   - Models used:
     - Logistic Regression
     - Random Forest Classifier
     - LightGBM
     - CatBoost
     - Simple DNN Model 
   - Evaluation metrics:
     - F1 Score

4. **Model Evaluation**
   - Confusion matrices
   - Metric comparison across models


## 📈 Model Results

The notebook evaluates multiple models. Among them, **Random Forest Classifier** and **Logistic Regression** were assessed using standard classification metrics. Final performance can be found in the notebook's evaluation section.

## 📌 Future Improvements

- Include more models (e.g., XGBoost, SVM)
- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
- Cross-validation
- Deployment as a web app using Streamlit or Flask

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
