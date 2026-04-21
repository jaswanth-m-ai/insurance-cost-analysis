# 📊 Medical Insurance Cost Analysis

## 📌 Project Overview

This project analyzes the impact of **smoking behavior on medical insurance charges** using statistical techniques and simple linear regression.
The goal is to understand patterns in the dataset and build a predictive model using a single independent variable.

---

## 🎯 Objectives

* Analyze the distribution of insurance charges using histogram
* Detect outliers using boxplot
* Study relationships using correlation analysis
* Perform hypothesis testing (t-test) between smokers and non-smokers
* Build and evaluate a simple linear regression model

---

## 🛠 Tools & Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

* Source: Medical Cost Personal Dataset
* Link: https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv

### Dataset Features:

* age
* sex
* bmi
* children
* smoker
* region
* charges

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were used:

* Histogram → distribution of charges
* Boxplot → detection of outliers
* Count plot → smoker vs non-smoker distribution
* Bar plot → average charges comparison
* Heatmap → correlation between variables

---

## 🧪 Statistical Analysis

* Hypothesis Testing (T-test) was performed to compare charges between smokers and non-smokers
* Result: Significant difference found (p-value < 0.05)

---

## 📈 Model Building

A **Simple Linear Regression** model was built using:

* Input Variable: Smoker (0 = No, 1 = Yes)
* Output Variable: Insurance Charges

---

## 📉 Model Performance

* R² Score: 0.66
* Mean Squared Error (MSE): 52,745,964
* Root Mean Squared Error (RMSE): 7,262

---

## 🔍 Overfitting Check

* Training R²: 0.61
* Testing R²: 0.66

👉 The model shows **no overfitting** and generalizes well.

---

## 📌 Key Insights

* Smokers have significantly higher insurance charges
* Smoking is a strong predictor of medical costs
* The model explains a large portion of variability using a single feature

---

## 🧾 Conclusion

The analysis confirms that smoking has a major impact on insurance expenses.
The regression model provides a reasonable prediction of charges and demonstrates the effectiveness of simple linear regression in real-world data analysis.

---

## 🚀 Future Scope

* Include more variables (age, BMI) for better accuracy
* Apply multiple linear regression
* Use advanced machine learning models

---

## 📎 References

* Scikit-learn Documentation: https://scikit-learn.org
* Pandas Documentation: https://pandas.pydata.org
* Dataset Source: GitHub Repository

---

## 👤 Author

**Jaswanth M**
AI & Data Science Student
