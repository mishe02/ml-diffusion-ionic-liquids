# Machine Learning Predictions of Diffusion in Ionic Liquids
This project applies machine learning models, including Random Forest, Gradient Boosting, Extra Trees, and Neural Networks to predict diffusion coefficients in bulk and confined ionic liquids using simple descriptors.

## Project Description
The goal is to investigate whether ML models can accurately predict diffusion behavior in ionic liquids based on a limited set of descriptors, such as density, temperature, molecular weight, and ion-specific slope parameters. The dataset used contains data for 29 ionic liquids and is stored in `Ionic1.xlsx`. 
The analysis focuses on predicting anion diffusion coefficients and comparing the performance of different ML methods.

## Notebook Contents
The notebook includes: 
- Data preprocessing and feature engineering  
- Exploratory data analysis (plots and correlations)  
- Regression models: Random Forest, Gradient Boosting, Extra Trees, Linear Regression, Neural Networks (MLPRegressor)  
- Model evaluation: MAE, MSE, R 
- Variance Inflation Factor (VIF) analysis
- Cross-validation using Yellowbrick 

## Tools & Libraries
- Python 3.x
- Pandas
- Numpy
- Statsmodels
- Matplotlib 
- Seaborn
- Scikit-learn
- Scipy
- Yellowbrick

## Dataset
- `Ionic1.xlsx` contains the input features and target diffusion coefficients.

 ## Usage
1. Clone the repository or download the files.
2. Ensure the `Ionic1.xlsx` file is in the same directory as the notebook.
3. Open `mishesprojectML2025.ipynb` in Jupyter Notebook.
4. Run the cells sequentially to reproduce the analysis and results.

## Optional
- You can install all required packages via pip:
```bash
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn scipy yellowbrick\
}
