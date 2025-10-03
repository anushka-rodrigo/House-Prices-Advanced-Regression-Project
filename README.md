# House Prices Advanced Regression Project

## Project Overview
This project focuses on predicting house sale prices using a variety of **advanced regression techniques**. It uses the [Ames Housing Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) as the basis for building predictive models. The goal is to predict the sale price (`SalePrice`) for houses in the test dataset based on the features in the training data.

The project is designed to showcase **data preprocessing, feature engineering, and model building**, combining both Python and R techniques.

---

## Dataset
The dataset contains:

- **Training data:** Includes 1460 observations with 81 features (numeric, categorical, and ordinal).  
- **Test data:** Includes 1459 observations where `SalePrice` is unknown.  

The dataset features include:

- **Numerical features:** Lot area, year built, overall quality, etc.  
- **Categorical features:** Neighborhood, garage type, exterior finish, etc.  
- **Target variable:** `SalePrice`.

---

## Project Workflow

### 1. Data Exploration (EDA)
- Analyzed distributions of numeric variables and their relationships with `SalePrice`.  
- Visualized categorical variables using countplots and boxplots.  
- Handled missing data by identifying patterns and imputing values or removing irrelevant columns.  
- Used correlation heatmaps to identify important features.

### 2. Feature Engineering
- Created new features such as **total square footage**, **age of the house**, and **interaction terms**.  
- Encoded categorical variables using one-hot encoding or label encoding depending on model requirements.  
- Applied transformations like log transformations to skewed numerical features to improve model performance.  

### 3. Model Building
- **Linear Models:** Linear Regression, LASSO, Ridge, ElasticNet.  
- **Tree-Based Models:** Random Forest, Gradient Boosting Machines (GBM), XGBoost.  
- **Ensemble Models:** Stacking multiple models to combine their predictions for better performance.  

### 4. Model Evaluation
- Used **cross-validation** on the training data to tune hyperparameters.  
- Evaluated model performance using **Root-Mean-Squared-Error (RMSE)** on the logarithm of predicted vs. actual values.  
- Selected the best-performing models for final predictions.

### 5. Submission
- Generated predicted `SalePrice` for the test dataset.  
- Prepared a submission file in the required format:


---

## Key Techniques Used
- **Data Cleaning:** Handling missing values, correcting data types, removing outliers.  
- **Feature Engineering:** Creating new features, encoding categorical variables, transforming skewed variables.  
- **Regularization:** Using LASSO and Ridge regression to prevent overfitting.  
- **Ensemble Methods:** Combining predictions from multiple models for better accuracy.  
- **Cross-Validation:** To select robust hyperparameters and avoid overfitting.  
- **Visualization:** Histograms, boxplots, pairplots, correlation heatmaps, and t-SNE for insights.

---

## Tools & Libraries
- **Python:** pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost.  
- **Jupyter Notebook & RMarkdown** for documenting the workflow.  

---

## Outcome
- The project demonstrates how to approach a real-world regression problem using a combination of statistical methods and machine learning.  
- Shows how to preprocess complex datasets, engineer features, build multiple predictive models, and evaluate them using proper metrics.  

