# Customer Churn Analysis

This project focuses on customer churn prediction using Python. It involves data preprocessing, exploratory data analysis (EDA), and machine learning model training to identify factors influencing customer churn and predict future churn likelihood.

## Key Features

- **Dataset**: Customer churn dataset containing attributes such as customer demographics, services, and payment details.
- **Data Preprocessing**:
  - Handled missing values and outliers.
  - Performed feature encoding for categorical data.
- **Exploratory Data Analysis**:
  - Visualized churn rates and trends across customer demographics.
  - Identified key factors contributing to churn, such as tenure, contract type, and payment method.
- **Model Training**:
  - Built machine learning models (e.g., Logistic Regression, Random Forest, XGBoost) to predict churn.
  - Evaluated models using accuracy, precision, recall, and F1-score.
- **Key Insight**: Customers using electronic checks as payment are more likely to churn.

## Tools & Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/th-ayyush/Customer-Churn-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to reproduce the analysis:
   ```bash
   jupyter notebook Churn_Analysis.ipynb
   ```
4. Explore the visualizations and model results in the notebook.

## Results

- **Best Model**: Random Forest achieved the highest F1-score of 0.85.
- **Churn Rate**: 26% of customers were predicted to churn.


