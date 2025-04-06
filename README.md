# Car Price Prediction

A machine learning project to predict the selling price of used cars based on various attributes such as mileage, model year, fuel type, transmission, and accident history. This project leverages data-driven techniques to deliver insights for buyers, sellers, and auto-market stakeholders.


## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Goals](#goals)  
- [Tools & Technologies](#tools--technologies)  
- [Approach](#approach)  
- [Author](#author)  


## Project Overview

This project aims to analyze and predict the price of used cars using machine learning algorithms. By conducting thorough exploratory data analysis (EDA), engineering meaningful features, and building regression models, we provide insights into key factors that influence car prices. This project not only serves as a portfolio piece but also strengthens core data science skills such as data cleaning, visualization, and model building.


## Dataset

The dataset used in this project is sourced from Kaggle and contains information on used cars sold in India. It includes features such as brand, model year, mileage, fuel type, engine details, transmission, accident history, and price.

📎 [Used Car Data - India (Kaggle)](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset)


## Goals

- Perform detailed EDA to uncover insights from the dataset.  
- Engineer new features (e.g., car age, total mileage).  
- Handle outliers and clean anomalies in data.  
- Train and evaluate regression models to predict car prices.  
- Identify the most important variables influencing pricing.


## Tools & Technologies

- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost  
- **Modeling Techniques**: Linear Regression, Random Forest, XGBoost Regressor  


## Approach

1. **Data Understanding**  
   - Load and inspect the structure and types of the data.  
   - Understand relationships and data distributions.  

2. **Data Preparation**  
   - Handle missing values and drop duplicates.  
   - Convert columns to appropriate data types.  
   - Drop irrelevant features such as engine configuration if needed.  

3. **Feature Engineering**  
   - Create new variables such as `car_age`, and binary flags for accidents.  
   - Clean and transform categorical and text data.  

4. **Exploratory Data Analysis (EDA)**  
   - Univariate, bivariate, and multivariate analysis.  
   - Visual exploration of how features influence price.  
   - Detection and treatment of outliers.  

5. **Modeling**  
   - Train multiple regression models.  
   - Apply scaling, encoding, and pipeline transformations.  
   - Perform hyperparameter tuning using RandomizedSearchCV.  

6. **Evaluation**  
   - Use metrics like RMSE, MAE, and R² to assess model performance.  
   - Compare different models and select the best performer.


## Author

**Michael Muthui Gatero**  
📧 gateromichael@gmail.com  
📞 +254 115 559110  
🌐 [LinkedIn]((https://www.linkedin.com/in/michael-gatero-915181311/)) 
