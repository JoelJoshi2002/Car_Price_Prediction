# Car Price Prediction

## Problem Description
A Chinese automobile company aims to enter the US market by setting up local manufacturing and competing with US and European automakers. To understand pricing dynamics, they have partnered with an automobile consulting firm to analyze factors affecting car prices in the American market.

## Business Goal
The goal is to build a predictive model that helps management understand the key variables influencing car prices. This model will assist in designing cars, optimizing business strategies, and setting competitive price levels.

## Dataset
The dataset consists of various car attributes and their prices, collected through market surveys in the US.

Dataset Link: [Car Price Dataset](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)


## Features & Workflow
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Identifying key factors affecting car prices.
- **Model Training & Evaluation**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regression
  - Support Vector Regression
  - **Gradient Boosting Regressor (Best Performing Model)**
- Conducted **feature importance analysis** to understand key pricing factors.
- **Hyperparameter Tuning**: Optimized Gradient Boosting  model using **RandomizedSearchCV** for improved performance.
- **Prediction on Test Data**: Evaluated using MAE, MSE, RMSE, and R² score.

## Results
- Best Model: **Gradient Boosting Regressor**
- After Hyperparameter Tuning:
  - **R² Score:** 0.889
  - **MAE:** 2089.8
  - **MSE:** 9591642.07
  - **RMSE:** 3097.03


## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train the model and test predictions.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Machine Learning Models** (Random Forest, SVR, Linear Regression, Decision Tree Regression, Gradient Boosting Regression)

## Future Improvements
- Include **deep learning models** for better accuracy.
- Deploy the model as a **web application** for real-time predictions.
- Integrate **more features** like car age, brand reputation, and mileage.

## Author
[Aneeta Abraham](https://github.com/AneetaAbhm)
