# InternIntelligence_PredictiveAnalytics
# 🧠 House Price Prediction using Linear Regression

This project was completed as part of the **Intern Intelligence Data Analytics Internship** under **Task 1: Predictive Analytics Model**. The goal was to build a machine learning model that predicts house prices based on historical data using linear regression.

---

## 🎯 Objective

Develop a predictive analytics model to forecast future house prices using a real-world dataset and machine learning techniques.

---

## 📁 Project Structure


---

## 🧰 Tools & Libraries Used

- **Python 3.x**
- **Jupyter Notebook / Google Colab**
- `pandas` – Data manipulation  
- `numpy` – Numerical computations  
- `matplotlib` & `seaborn` – Visualization  
- `scikit-learn` – Machine learning models and evaluation  

---

## 📊 Dataset Overview

The dataset used is the **Boston Housing Dataset**, which provides information about different housing features in Boston and the corresponding median value of owner-occupied homes.

### 🔑 Features (Independent Variables)

- `CRIM`: Crime rate per capita  
- `ZN`: Proportion of residential land zoned for large lots  
- `INDUS`: Proportion of non-retail business acres  
- `CHAS`: Charles River dummy variable  
- `NOX`: Nitric oxide concentration  
- `RM`: Average number of rooms per dwelling  
- `AGE`: Proportion of old buildings  
- `DIS`: Distance to employment centers  
- `RAD`: Access to highways  
- `TAX`: Property-tax rate  
- `PTRATIO`: Pupil-teacher ratio  
- `B`: Proportion of Black population  
- `LSTAT`: Percentage of low-status population  

### 🎯 Target Variable

- `House price`: Median value of owner-occupied homes (in $1000s)

---

## 🧼 Data Preprocessing

- Loaded the dataset into a Pandas DataFrame
- Identified and filled missing values using column means
- Conducted exploratory data analysis using `.describe()`, `.isnull()`, and `.corr()`
- Visualized correlations using a heatmap to determine feature relationships

---

## 📈 Model Building

- **Model Used**: Linear Regression (`LinearRegression` from `sklearn`)
- Split the dataset into **80% training** and **20% testing**
- Trained the model on training data
- Made predictions on both training and test data
- Evaluated model using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
- Visualized actual vs predicted prices using a scatter plot

---

## ✅ Results & Evaluation

- Scatter plot showed a strong linear relationship between actual and predicted values
- Model performs very well on test data
- Best predictors: `RM` (positive), `LSTAT` and `PTRATIO` (negative)

---

## 💡 Key Insights

- Linear Regression is effective for this dataset due to linear feature-target relationships.
- `RM` (average number of rooms) has the strongest positive impact on price.
- `LSTAT` (low-income population %) is strongly negatively correlated with price.
- With minimal feature engineering, we achieved a low RMSE.

---

## 🚀 Future Improvements

- Try advanced models like:
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Apply feature scaling (e.g., StandardScaler)
- Use GridSearchCV for hyperparameter tuning
- Implement K-Fold Cross Validation for robust model evaluation

---

> 🔒 This project is for educational and internship purposes only.
