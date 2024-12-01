website: https://mlprojcreditriskmodel-kishorefinance.streamlit.app/
# ML_Credit_Risk_Model
# Credit Risk Modeling App

## Overview
The **Credit Risk Modeling App** is designed to assess credit risk using various machine learning models. It incorporates advanced data preprocessing techniques, visualizations, and model evaluation methods to ensure robust predictions. Built using **Streamlit**, the app provides a user-friendly interface for real-time analysis.

## Key Features
- **Data Preprocessing**:
  - Handling missing values, outlier removal, and data cleaning.
  - Scaling features using **MinMax Scaler**.
- **Train-Test Contamination**: Avoids data leakage to ensure reliable model performance.
- **Feature Engineering**: 
  - Analysis using **Variance Inflation Factor (VIF)** to handle multicollinearity.
- **Modeling Techniques**:
  - Regression, Decision Trees, **XGBoost**, and more.
  - Hyperparameter optimization using **Optuna**.
- **Visualization**: 
  - **KDE plots** used for visualizing the distribution of defaulters and non-defaulters.
- **Evaluation**: 
  - Model performance measured using **Gini Coefficient** and **KS Statistics**.
  - Rank ordering and statistical evaluation for predictive power.

## Installation
Follow these steps to set up the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ml_proj_credit_risk_model.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ml_proj_credit_risk_model
    ```

3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## How It Works
1. **Data Input**: The user provides input data like age, income, and past defaults.
2. **Data Cleaning**: The app cleans the input data by removing outliers and scaling the data.
3. **Visualization**: The app generates visualizations like **KDE plots** to show the distribution of features.
4. **Modeling**: The app trains multiple machine learning models (Regression, Decision Trees, XGBoost, etc.).
5. **Evaluation**: Model performance is evaluated using metrics such as the **Gini Coefficient** and **KS Statistics**.

## Technology Stack
- **Front-end**: Streamlit
- **Back-end**: Python
- **Libraries**: 
  - pandas, numpy, seaborn, scikit-learn
  - XGBoost, Optuna for optimization
  - matplotlib for visualization

## Model Evaluation
- **Gini Coefficient**: Measures the model's discriminatory power.
- **KS Statistics**: Helps assess how well the model distinguishes between different risk classes.

### Contact

For any questions or issues, please contact:  
**Email:** kishoresj1807@gmail.com
