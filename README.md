# Telecom Churn Prediction 📞

Author- Rishav Kumar


## Overview

This project aims to predict customer churn in a telecom company. Churn prediction is critical for telecom companies to identify customers who are likely to leave and take proactive measures to retain them. By using machine learning techniques, we can analyze customer data and predict the likelihood of churn.

## Dataset

The dataset consists of customer information including demographic details, account information, and service usage patterns. The main features include:

- **CustomerID**
- **Gender**
- **SeniorCitizen**
- **Partner**
- **Dependents**
- **Tenure**
- **PhoneService**
- **MultipleLines**
- **InternetService**
- **OnlineSecurity**
- **OnlineBackup**
- **DeviceProtection**
- **TechSupport**
- **StreamingTV**
- **StreamingMovies**
- **Contract**
- **PaperlessBilling**
- **PaymentMethod**
- **MonthlyCharges**
- **TotalCharges**
- **Churn** (Target variable)

## Project Structure

├── data
│   └── telecom_churn.csv        # Dataset file
├── notebooks
│   └── churn_prediction.ipynb   # Jupyter notebook with analysis
├── src
│   └── data_preprocessing.py    # Data preprocessing script
│   └── data_visualization.py    # Data visualization script
│   └── model_training.py        # Model training script
├── README.md                    # Project README file


## Analysis Steps

1. **Data Loading and Exploration**
   - Load the dataset and understand its structure.
   - Perform basic statistical analysis.

2. **Data Visualization**
   - Visualize the data to understand the distribution of features.
   - Create plots to observe relationships between features and churn.

3. **Data Preprocessing**
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.

4. **Model Training and Evaluation**
   - Split the data into training and testing sets.
   - Train machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
   - Evaluate the models using accuracy, precision, recall, F1-score, and ROC-AUC.
   - All type of Classification is Applied
  
  
## Results

The best-performing model in this analysis is different type Classification with an accuracy of 80%. Detailed results and visualizations can be found in the [Jupyter notebook](notebooks/churn_prediction.ipynb).
