💼 Salary Prediction using Linear Regression (Without Scikit-Learn)
📘 Overview

This is a simple Python project created to build a clear understanding of how Linear Regression works from scratch — without using any machine learning libraries like scikit-learn.

The project predicts an employee’s salary based on their years of experience using only basic mathematical formulas and NumPy operations.

🧠 Objective

To manually calculate the best-fit line (y = m*x + c) and understand how a machine learning model learns the relationship between features and output.

🧩 Dataset

File: traning_set.csv
Columns:

YearsExperience — Number of years of professional experience

Salary — Annual salary corresponding to experience

The dataset is small and ideal for learning regression basics.

⚙️ Technologies Used

Python 3

Jupyter Notebook

Libraries:

pandas — For reading and handling data

numpy — For performing mathematical operations

matplotlib — For plotting graphs and regression line

🚀 Steps Involved

Import libraries (pandas, numpy, matplotlib)

Load and explore the dataset

Plot the data to visualize the relationship between experience and salary

Calculate slope (m) and intercept (c) using mathematical formulas:

𝑚
=
𝑛
(
Σ
𝑥
𝑦
)
−
(
Σ
𝑥
)
(
Σ
𝑦
)
𝑛
(
Σ
𝑥
2
)
−
(
Σ
𝑥
)
2
m=
n(Σx
2
)−(Σx)
2
n(Σxy)−(Σx)(Σy)
	​

𝑐
=
Σ
𝑦
−
𝑚
(
Σ
𝑥
)
𝑛
c=
n
Σy−m(Σx)
	​


Predict salaries using:

𝑦
𝑝
𝑟
𝑒
𝑑
=
𝑚
×
𝑥
+
𝑐
y
pred
	​

=m×x+c

Plot the regression line to visualize predictions

(Optional) Calculate MSE or R² manually to check accuracy

📈 Example Output

Slope (m): 9449.96

Intercept (c): 25792.20

Predicted Salary (for 5 years experience): ₹77,042

R² Score: 0.96 (approx.)

(Values depend on dataset)

💡 Learnings

How Linear Regression works mathematically

Deriving slope and intercept manually

Predicting new data points using simple equations

Visualizing data and best-fit line

🗂️ Folder Structure
Linear_Regression_Understanding/
│
├── Linear_regreesion.ipynb   # Main Jupyter Notebook
├── traning_set.csv           # Dataset
└── README.md                 # Documentation

🎯 Purpose

This is a beginner-friendly project built only to understand the concept of Linear Regression and how predictions work behind the scenes — before using advanced ML libraries.

👨‍💻 Author

Anirudh Chaudhari
Aspiring AI/ML Engineer | Python & Computer Vision Enthusiast
🔗 LinkedIn
