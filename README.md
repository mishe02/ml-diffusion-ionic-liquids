{\rtf1\ansi\ansicpg1252\cocoartf2820
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Machine Learning Predictions of Diffusion in Ionic Liquids\
\
This project applies machine learning models, including Random Forest, Gradient Boosting, Extra Trees, and Neural Networks to predict diffusion coefficients in bulk and confined ionic liquids using simple descriptors.\
\
## Project Description\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 The goal is to investigate whether ML models can accurately predict diffusion behavior in ionic liquids based on a limited set of descriptors, such as density, temperature, molecular weight, and ion-specific slope parameters. The dataset used contains data for 29 ionic liquids and is stored in `Ionic1.xlsx`. \
The analysis focuses on predicting anion diffusion coefficients and comparing the performance of different ML methods.\
\
## Notebook Contents\
The notebook includes:  \
- Data preprocessing and feature engineering  \
- Exploratory data analysis (plots and correlations)  \
- Regression models: Random Forest, Gradient Boosting, Extra Trees, Linear Regression, Neural Networks (MLPRegressor)  \
- Model evaluation: MAE, MSE, R\'b2  \
- Variance Inflation Factor (VIF) analysis  \
- Cross-validation using Yellowbrick  \
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 ## Tools & Libraries\
- Python 3.x\
- Pandas\
- Numpy\
- Statsmodels\
- Matplotlib \
- Seaborn\
- Scikit-learn\
- Scipy\
- Yellowbrick (for model evaluation visualization)\
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 ## Dataset\
- `Ionic1.xlsx` \'96 contains the input features and target diffusion coefficients.\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 ## Usage\
1. Clone the repository or download the files.\
2. Ensure the `Ionic1.xlsx` file is in the same directory as the notebook.\
3. Open `notebook.ipynb` in Jupyter Notebook.\
4. Run the cells sequentially to reproduce the analysis and results.\
\
## Optional\
- You can install all required packages via pip:\
```bash\
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn scipy yellowbrick\
}