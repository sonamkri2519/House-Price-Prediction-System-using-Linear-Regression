# House-Price-Prediction-System-using-Linear-Regression
A machine learning project that predicts house prices based on property features such as area, bedrooms, and bathrooms.

#Project Overview
The goal of this project is to build a predictive model that estimates
house prices using **Linear Regression**.\
By analyzing housing data, the model learns patterns between house
features and property prices.

This project demonstrates the complete **Data Science workflow**
including:

-   Data preprocessing
-   Exploratory Data Analysis (EDA)
-   Machine learning model training
-   Model evaluation
-   Visualization of results

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit‑learn
-   Streamlit

------------------------------------------------------------------------

## 📊 Project Workflow

1.  Data Collection
2.  Data Cleaning & Preprocessing
3.  Exploratory Data Analysis
4.  Feature Selection
5.  Model Training using Linear Regression
6.  Model Evaluation
7.  Price Prediction

------------------------------------------------------------------------

## 📈 Visualizations

The project includes several visualizations:

-   Scatter Plot (Area vs Price)
-   Correlation Heatmap
-   Predicted vs Actual Price Graph

These help understand relationships between features and house prices.

------------------------------------------------------------------------

## 🤖 Machine Learning Model

The model used in this project is **Linear Regression**, a supervised
learning algorithm used for predicting continuous values.

Linear Regression Formula:

Price = b0 + b1X1 + b2X2 + ... + bnXn

Where: - Price → Predicted house price - X → House features - b → Model
coefficients

------------------------------------------------------------------------

##  Model Performance

Evaluation metrics used:

-   Mean Absolute Error (MAE)
-   Mean Squared Error (MSE)
-   R² Score

Example Result:

R² Score = **0.87**

This means the model explains **87% of the variance in house prices**.

------------------------------------------------------------------------

##  Streamlit Web App

A simple web application allows users to input house features and get
price predictions instantly.

Run the app:

``` bash
streamlit run app.py
```

------------------------------------------------------------------------

##  Project Structure

    house-price-prediction/
    │
    ├── dataset/
    ├── notebook/
    ├── app.py
    ├── model.pkl
    ├── README.md
    └── requirements.txt

------------------------------------------------------------------------

##  Future Improvements

-   Use larger real estate datasets
-   Implement advanced ML algorithms (Random Forest, XGBoost)
-   Deploy the model as a web application

------------------------------------------------------------------------

##  Author

**Sonam Kumari**\
Aspiring Data Analyst \| Learning SQL, Power BI, Python & AI
