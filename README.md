## 📈 Simple Linear Regression – Machine Learning Project

This project demonstrates the implementation of Simple Linear Regression using Python and Scikit-learn.
The goal is to model the relationship between an independent variable (X) and a dependent variable (Y) and make predictions.

---

## 🚀 Project Overview

Simple Linear Regression is one of the most fundamental supervised learning algorithms.
It establishes a linear relationship between two variables using the equation:

- 𝑌=𝑏0+𝑏1𝑋

- Where:
 - Y → Dependent variable
 - X → Independent variable
 - b₀ → Intercept
 - b₁ → Slope

---

## 🛠 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🔹 Steps Performed
1️⃣ Importing Libraries
- Loaded essential libraries for data handling, visualization, and modeling.

2️⃣ Importing Dataset
- Dataset loaded using Pandas
- Independent variable (X)
- Dependent variable (Y)

3️⃣ Splitting Dataset
- Dataset divided into:
 - 80% Training set
 - 20% Test set
 - train_test_split(test_size=0.2, random_state=0)

4️⃣ Training the Model
- Model trained using:
 - from sklearn.linear_model import LinearRegression
 - regressor = LinearRegression()
 - regressor.fit(X_train, y_train)

5️⃣ Making Predictions
- y_pred = regressor.predict(X_test)

6️⃣ Visualization
- Training set results plotted
- Test set predictions plotted
- Regression line visualized using Matplotlib

## 📊 Model Interpretation
- The model learns:
- Best-fit regression line
- Relationship between independent and dependent variable
- Predicted values based on learned slope and intercept

---











