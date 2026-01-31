# House Price Prediction using Linear Regression

This project is made by a complete linear regression pipeline to predict house prices using the California Housing dataset.  
The goal is to understand model training, evaluation, and interpretation using real-world numerical data.

## Dataset
- Source: California Housing dataset (scikit-learn)
- Target variable: Median house value
- Features include median income, house age, average rooms, population, latitude, longitude, etc.

## Approach
1. Loaded the dataset using scikit-learn  
2. Split data into training and testing sets (80/20) (one can use other ratio too)   
3. Trained a Linear Regression model  
4. Evaluated performance using RMSE and R² score  
5. Interpreted coefficients to analyze feature impact  
6. Standardized features and retrained the model for better interpretability  

## Results
- Median income and geographic location were the strongest predictors of house prices.
- Population-related features showed minimal influence.
- Feature scaling improved coefficient interpretability without significantly changing performance.

## Key Learnings
- Linear regression coefficients are meaningful only when features are on comparable scales.
- Standardization is essential for proper interpretation.
- Model evaluation must be done on unseen test data.

## Tools Used
- Python
- NumPy
- pandas
- scikit-learn
- Google Colab

## How to Run
Open the notebook and run all cells sequentially.

