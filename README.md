# **Customer Churn Prediction using ML Models**

## Assignment Overview
1) This project focuses on predicting customer churn using a telecom dataset.
2) We explore various machine learning models such as **Linear Regression**, **Logistic Regression**, and **Generalized Additive Models (GAMs)** to understand both linear and non-linear relationships between customer features and churn.
3) The goal is to build interpretable models and compare their performance to provide insights into customer churn behavior.

## Implementation of Models

### 1. Linear Regression
- Churn is treated as a continuous variable.
- Focuses on understanding the linear impact of features on target variable through coefficients.
- **Performance Metrics**:
  - R² (Coefficient of Determination)
  - Mean Squared Error (MSE)
- Linear regression was found to be less accurate due to the binary nature of the target variable, making it less effective for precise churn prediction.


### 2. Logistic Regression
- Churn is treated as a binary variable.
- Evaluates feature importance and checking whether the assumptions have been met.
- **Performance Metrics**:
  - Accuracy
  - ROC-AUC Score
  - Classification Report
-  Logistic regression performed well in predicting churn and provided interpretable coefficients for business insights.

### 3. Generalized Additive Model (GAM)
- Designed to capture non-linear relationships between features and churn.
- Fits splines to model flexible feature effects for better precision.
- **Performance Metrics**:
  - Accuracy
  - ROC-AUC Score
  - Classification Report
- GAMs outperformed linear models in terms of flexibility and interpretability for non-linear features

**Recommendation**: 
1) Use **Logistic Regression** for linear features which is very interpretable and yields a good accuracy. 
2) If non linear features are found to be critical use **GAM** by making some adjustments.


## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/johnjoel2001/ML_Interpretability.git
   cd ML_Interpretability
   ```
2. Run the main.ipynb
3. The requirements are listed in the first cell.


## Reference: 
1. https://github.com/AIPI-590-XAI/Duke-AI-XAI/tree/main/interpretable-ml-example-notebooks


