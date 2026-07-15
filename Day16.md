Daily Diary – Day 16
  
Date: 16 July 2026

Topic Covered: Basics of Linear Regression

What I Did Today:
Today, I took my first step into the world of machine learning by studying the basics of Linear Regression, one of the most fundamental and widely used algorithms for predictive modeling. I learned the theory 
behind it and also implemented a simple example using Python.

Key Concepts Learned:
1. What is Linear Regression?
Linear regression is a supervised learning algorithm used to predict a continuous numerical value.

It models the relationship between one independent variable (X) and one dependent variable (Y) using a straight line:
𝑌
=
𝑚
𝑋
+
𝑐
Y=mX+c

The goal is to find the best-fitting line (also called the regression line) by minimizing the error between the predicted and actual values.

2. Simple Linear Regression:
Implemented using a dataset with one independent and one dependent variable.

Practiced using libraries like:

scikit-learn (LinearRegression)

pandas for data handling

matplotlib for plotting the regression line

3. Key Functions Used:
LinearRegression().fit(X, y) – To train the model

.predict(X) – To make predictions

.score(X, y) – To evaluate accuracy (R² score)

🔧 Practical Implementation:
Used a small dataset (e.g., hours studied vs. marks scored)

Trained a linear regression model using scikit-learn

Visualized the best-fit line using matplotlib.pyplot.plot()

Understood how the slope (coefficient) and intercept affect predictions

Observations:
Linear regression works best when the data has a linear relationship.

Outliers and skewed data can significantly affect the performance of the model.

The R² score helps evaluate how well the line fits the data.

Tools & Libraries Used:
Pandas – For loading and preparing the data

NumPy – For numerical operations

Matplotlib/Seaborn – For visualization

Scikit-learn – For building and evaluating the linear regression model
