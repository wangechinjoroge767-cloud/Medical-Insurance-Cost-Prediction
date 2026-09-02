# Medical-Insurance-Cost-Prediction

# Medical Insurance Cost Prediction

## 📌 Project Overview

This project uses the **Medical Cost Personal Dataset** to explore the factors that influence individual medical insurance charges and to build a machine learning model that can predict those charges.

The main goal was to understand the data, identify patterns, and compare different machine learning models to see which one could make the most accurate predictions.

## 📊 Dataset

The dataset contains information about individuals, including:

* Age
* Sex
* BMI
* Number of children
* Smoking status
* Region
* Medical insurance charges

The target variable in this project is **`charges`**, which represents the individual's medical insurance cost.

## 🔍 Exploratory Data Analysis

I explored the dataset to understand its structure and identify relationships between the different variables and insurance charges.

Some of the analysis included:

* Checking the dataset structure and data types
* Checking for missing values
* Examining the distribution of insurance charges
* Comparing insurance charges between smokers and non-smokers
* Exploring the relationship between age and insurance charges
* Investigating which features were most important for prediction

## 🤖 Machine Learning

I tested three regression models:

1. **Linear Regression**
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor**

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## 📈 Model Results

| Model                 |          MAE |         RMSE |   R² Score |
| --------------------- | -----------: | -----------: | ---------: |
| Linear Regression     |     4,181.19 |     5,796.28 |     0.7836 |
| Random Forest         |     2,550.08 |     4,576.30 |     0.8651 |
| **Gradient Boosting** | **2,443.48** | **4,329.57** | **0.8793** |

### 🏆 Best Model

**Gradient Boosting** produced the best results among the three models tested.

It achieved an **R² score of 0.8793**, meaning it was able to explain approximately **87.9% of the variation in medical insurance charges** in the test data.

It also had the lowest MAE and RMSE of the three models.

## 💡 Key Findings

The analysis showed that different personal and health-related characteristics can have an important relationship with medical insurance costs.

The feature-importance analysis was also used to understand which variables contributed most to the model's predictions.

One of the interesting parts of the project was seeing how machine learning can move beyond simply looking at the data and actually use the patterns in the data to make predictions.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter/Kaggle Notebook
* Joblib

## 📁 Project Files

```text
Medical-Insurance-Cost-Prediction/
│
├── medical_insurance_prediction.ipynb
├── gradient_boosting_insurance_model.pkl
└── README.md
```

## 🚀 Future Improvements

Some possible improvements for this project would be:

* Hyperparameter tuning
* Testing additional machine learning algorithms
* Using cross-validation
* Improving feature engineering
* Deploying the trained model as a simple prediction application


This project was developed as part of my journey in **Data Science and Machine Learning**, with the goal of applying what I have learned to a real-world dataset.
