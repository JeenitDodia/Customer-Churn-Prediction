# 📊 Customer Churn Prediction using Machine Learning

## Project Overview

This project develops a Machine Learning model to predict whether a telecom customer is likely to leave the service (churn) based on customer demographics, subscription details, and billing information.

The project follows a complete Machine Learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, data preprocessing, feature scaling, model building, model evaluation, and business insight generation. Multiple classification algorithms were trained and compared to identify the best-performing model for customer churn prediction.

---

## Dataset

This project uses the Telco Customer Churn Dataset, which is publicly available on Kaggle.

To run this project, download the dataset from the original source and place the following file in the same directory as the notebook:

WA_Fn-UseC_-Telco-Customer-Churn.csv
Dataset Source:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Project Workflow

### 1. Data Loading

Loaded the dataset using Pandas and inspected its structure, columns, and data types.

### 2. Dataset Inspection

Performed an initial analysis using:

- head()
- info()
- describe()
- shape
- dtypes
- Missing Value Check

### 3. Data Cleaning

Performed the following preprocessing steps:

- Identified missing values
- Converted TotalCharges to numeric
- Filled missing values
- Removed the customerID column
- Prepared the dataset for analysis

### 4. Exploratory Data Analysis (EDA)

Analyzed:

- Customer Churn Distribution
- Gender Distribution
- Contract Type Analysis
- Payment Method Analysis
- Internet Service Analysis
- Monthly Charges Distribution
- Tenure Analysis
- Correlation Heatmap

### 5. Feature Engineering

Prepared the dataset by:

- Separating input features and target variable
- Encoding categorical variables using One-Hot Encoding

### 6. Data Preprocessing

Performed:

- Train-Test Split
- Feature Encoding

### 7. Feature Scaling

Applied StandardScaler to normalize numerical features before model training.

### 8. Machine Learning Models

Implemented the following models:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### 9. Model Evaluation

Evaluated each model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix
- ROC Curve

### 10. Feature Importance

Analyzed feature importance using the Random Forest model to identify the most influential factors contributing to customer churn.

### 11. Model Comparison

Compared the performance of all machine learning models using multiple evaluation metrics to identify the best-performing model.

### 12. Business Insights

Generated meaningful business insights to help telecom companies improve customer retention strategies.

---

## Key Insights

- Customers with month-to-month contracts have a higher likelihood of churning.
- Customers with higher monthly charges are more likely to leave the service.
- Customers with longer tenure are generally more loyal.
- Electronic Check is associated with a higher churn rate than other payment methods.
- Contract type and tenure are among the most influential factors affecting customer churn.
- Machine Learning models can effectively identify customers who are at high risk of leaving, enabling businesses to implement targeted retention strategies.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Feature Scaling
- Machine Learning Classification
- Model Evaluation
- ROC Curve Analysis
- Feature Importance Analysis
- Business Insight Generation

---

## How to Run the Project

### 1. Download the Dataset

Download the dataset from Kaggle and place the following file in the project folder:

WA_Fn-UseC_-Telco-Customer-Churn.csv
Dataset Source:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### 2. Install the Required Libraries

pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib jupyter
### 3. Run the Notebook

jupyter notebook Customer_Churn_Prediction.ipynb
---

## Repository Structure

Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
└── README.md
> Note: The dataset is not included in this repository. Please download it from the Kaggle link above before running the notebook.

---

## Project Conclusion

This project demonstrates a complete end-to-end Machine Learning workflow for predicting customer churn in the telecommunications industry. The dataset was cleaned, analyzed, preprocessed, and used to train multiple classification models.

The performance of Logistic Regression, Random Forest, and XGBoost was evaluated using various classification metrics, including Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC Curve. Feature importance analysis identified the key factors influencing customer churn, while business insights highlighted opportunities for improving customer retention.

Overall, this project strengthened practical skills in data preprocessing, machine learning model development, evaluation, and business interpretation, providing valuable experience in solving real-world customer analytics problems.

---

## Author

Jeenit Dodia

Computer Science Engineering Student

Aspiring AI/ML Engineer
