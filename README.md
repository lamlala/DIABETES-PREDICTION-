# 🧠 Diabetes Prediction Using Machine Learning

This project applies machine learning techniques to predict the likelihood of a person having diabetes based on diagnostic measurements. The dataset includes various medical predictor variables and one target variable indicating diabetes presence.

## 📁 Project Structure

```
.
├── diabetes-prediction.ipynb   # Jupyter Notebook with full analysis and modeling
├── README.md                   # Project overview and usage guide
```

## 📊 Dataset

- Source: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
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
   - Evaluation metrics:
     - Accuracy
     - Precision
     - Recall
     - F1 Score

4. **Model Evaluation**
   - Confusion matrices
   - Metric comparison across models

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook diabetes-prediction.ipynb
   ```

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### `requirements.txt`:
```txt
pandas
numpy
scikit-learn
matplotlib
seaborn
```

## 📈 Model Results

The notebook evaluates multiple models. Among them, **Random Forest Classifier** and **Logistic Regression** were assessed using standard classification metrics. Final performance can be found in the notebook's evaluation section.

## 📌 Future Improvements

- Include more models (e.g., XGBoost, SVM)
- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
- Cross-validation
- Deployment as a web app using Streamlit or Flask

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
