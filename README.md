
# Predicting Loan Eligibility using H20.ai and Deep Learning Algorithms

## Project Overview

This project sought to implement a statistical model to predict loan eligibility for individuals applying for loans. Using a comprehensive dataset of over 100,000 loan records, the model I developed assessed various factors to determine the likelihood of loan repayment. 

The process involved extensive data analysis, cleaning, feature engineering, and model training using state-of-the-art machine learning algorithms.

## Business Objective

The ultimate goal was to enhance decision-making processes in loan issuance, ensuring loans are granted to applicants with a high likelihood of repayment.

## Tech Stack

- **Language:** Python
- **Libraries:** Scikit-learn, H2O, pandas, numpy, Flask, Seaborn, Matplotlib
- **Containerization:** Docker

## Dataset Description

The dataset comprised anonymized synthetic data, designed to mimic real loan application records. It included various features such as loan amount, credit score, employment history, annual income, and more.

## Approach

1. **EDA:** Conductd missing data analysis, data imputation, bad feature removal, and feature distribution analysis.
2. **Data Cleaning / Pre-processing:** Applied One Hot Encoding for categorical variables, and Label Encoding for discretization.
3. **Feature Engineering:** Created non-linear feature combinations and add pre-calculated priors.
4. **Standardizing Data:** Used standard scaler for data normalization.
5. **Modelling:** Leveraged Random Forest, Boosting Models, Light GBM, XGBoost, GBT, and Neural Networks.
6. **Hyperparameter Tuning:** Used GridSearchCV for model optimization.
7. **Final Model Selection:** Based on the best AUCPR score, alongside tracking AUC and F1 score.
8. **Deployment:** Deployed the model using Flask API within a Docker container.

## Modular Code Overview

After extracting `modular_code.zip`, you'll find the following structure:

- `input/`: Contains all data files for analysis.
- `src/`: Core project directory with modularized code for all steps, including ML pipeline functions and deployment scripts.
- `output/`: Stores trained models as reusable files.
- `lib/`: Reference folder with original IPython notebooks.

### src Folder Contents

- `ML_pipeline/`: Python files with functions for each step in the ML pipeline.
- `deployment/`: Files related to Flask API deployment.
- `engine.py`: Central script calling functions from `ML_pipeline`.

## Project Takeaways

Through this project, I demonstrated hands-on experience with:
- Data analysis and visualization.
- Data preprocessing and feature engineering.
- Model training and evaluation with H2O's machine learning algorithms.
- Model deployment using Docker and Flask.


## Contributing

Contributions to improve the model or extend the project are welcome. Please follow the standard pull request process to submit your contributions.
