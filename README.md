# house-price-prediction-ml
🏠 House Price Prediction using Machine Learning


📌 Overview

This project develops a machine learning model to predict house prices based on structural and categorical features. The goal is to understand how different attributes influence housing prices and build an accurate predictive model.

📊 Dataset

The dataset contains various features describing residential homes, including:

Numerical features (e.g., area, number of rooms, year built)

Categorical features (e.g., neighborhood, house style, quality)

Target variable:

SalePrice

⚙️ Methodology

Data preprocessing

Selected numerical features

Applied one-hot encoding to categorical variables

Handled missing values using median imputation

Modeling

Trained Decision Tree and Random Forest models

Tuned hyperparameters (number of trees, depth)

Evaluation

Used 5-fold cross-validation

Metric: Mean Absolute Error (MAE)

 📊 Model Comparison

Two models were evaluated using 5-fold cross-validation:

- Decision Tree MAE: ~24,900  
- Random Forest MAE: ~17,600  

Random Forest significantly outperformed the Decision Tree, demonstrating better generalization.


🧪 Evaluation Method

Model performance was evaluated using 5-fold cross-validation to ensure reliable and robust error estimates.

🔍 Key Insights

OverallQual is the most important feature (~57% importance)

Larger living area strongly increases price

Random Forest significantly outperforms Decision Tree

Handling missing values and using all features improved performance substantially

🧠 Conclusion

This project highlights the importance of feature engineering and model selection in machine learning. It also shows how domain-relevant features can strongly influence predictive performance.
