#  Student Performance Prediction – End-to-End Machine Learning Project

## 📌 Overview

This project is an end-to-end Machine Learning pipeline developed to predict student performance based on demographic and academic features.

The solution includes:
- Data analysis (EDA)
- Feature engineering
- Model training and evaluation
- Pipeline automation
- Flask API for predictions

---

##  Problem Statement

Educational institutions often need to identify students at risk of underperforming.  
This project aims to predict student exam performance using demographic and academic data.

---

##  Dataset

The dataset contains features such as:

- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Reading score
- Writing score

Target variable:
- Math score (Predicted)

---

##  Machine Learning Pipeline

The project follows a structured ML workflow:

1. Data Ingestion
2. Data Transformation
   - Encoding categorical variables
   - Feature scaling
3. Model Training
   - Multiple models tested
   - Hyperparameter tuning
4. Model Evaluation
5. Model Serialization
6. Deployment-ready prediction pipeline

---

##  Models Tested

- Linear Regression
- Decision Tree Regressor
- Random Forest
- XGBoost

The best-performing model was selected based on evaluation metrics.

---

##  Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## API endpoint   -- post   /predictdata

```
{
  "gender": "male",
  "ethnicity": "group A",
  "parental_level_of_education": "bachelor's degree",
  "lunch": "standard",
  "test_preparation_course": "none",
  "reading_score": 72,
  "writing_score": 74
}
```
response
```
{
  "prediction": 00.00
}

```

## Technologies Used 

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Flask



