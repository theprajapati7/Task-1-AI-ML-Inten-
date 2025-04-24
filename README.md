# Task-1-AI-ML-Inten-
Data Cleaning & Preprocessing Project 🧹🔧
Objective 🎯
This project demonstrates how to clean and preprocess raw data for machine learning. It involves handling missing values, encoding categorical features, scaling numerical data, and detecting/removing outliers.

Tools & Libraries Used 🛠️
Python: Main programming language 🐍

Pandas: For data manipulation and analysis 📊

NumPy: For numerical operations 🔢

Matplotlib: For data visualization 📉

Seaborn: For statistical data visualization 📈

Scikit-learn: For standardization and normalization 🤖

Dataset 📂
The dataset used in this project consists of customer information, including:

customer_id: Unique identifier for each customer 🆔

age: Customer's age 🎂

gender: Gender of the customer (Male/Female) 👨‍🦰👩‍🦳

annual_income: The annual income of the customer 💵

purchase_amount: The total amount the customer has spent 🛒

city: The city the customer lives in 🏙️

signup_date: Date when the customer signed up 🗓️

Steps Completed ✅
Exploring the Data 🔍:

Loaded the dataset and explored its structure.

Checked for missing values and identified data types.

Handling Missing Values 💧:

Imputed missing numerical values using mean/median.

Filled missing categorical values using the mode (most frequent value).

Encoding Categorical Features 🏷️:

Converted categorical variables into numerical representations using Label Encoding for binary features and One-Hot Encoding for multi-class features.

Normalization/Standardization 📏:

Applied Standardization (Z-score scaling) to numerical features to ensure all features are on the same scale.

Outlier Detection & Removal 🚫:

Visualized outliers using Boxplots.

Removed outliers based on the Interquartile Range (IQR).
