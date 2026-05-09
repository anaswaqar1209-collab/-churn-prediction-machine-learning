# Customer Churn Prediction using Machine Learning

## Project Overview

This project focuses on predicting customer churn for a telecom company using machine learning techniques.

The objective is to identify customers who are likely to leave a service so businesses can take proactive retention measures, reduce revenue loss, and improve customer satisfaction.

---

## Business Problem

Customer churn is one of the biggest challenges for subscription-based businesses.

Retaining existing customers is often more cost-effective than acquiring new ones. This project uses predictive analytics and machine learning to help businesses detect high-risk customers early and make data-driven retention decisions.

---

## Dataset

### Telco Customer Churn Dataset

The dataset contains more than 7,000 customer records with features such as:

- Customer demographics
- Contract information
- Monthly charges
- Internet services
- Payment methods
- Customer tenure
- Churn status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Machine Learning Models

The following machine learning models were implemented and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Evaluation Metrics

Model performance was measured using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## Key Insights

The analysis revealed several important business insights:

- Customers with month-to-month contracts showed a higher churn probability
- Higher monthly charges increased churn likelihood
- Customers with shorter tenure were more likely to churn
- Long-term customers demonstrated stronger retention stability

---

## Project Structure

```bash
customer-churn-prediction/
│
├── data/
├── notebooks/
├── images/
├── models/
├── README.md
├── requirements.txt
└── churn_prediction.ipynb
```


## Results

The best-performing model optimized recall, enabling more effective identification of at-risk customers.

This solution can help businesses:

Reduce customer churn
Improve customer retention strategies
Increase customer lifetime value
Support data-driven business decisions

## How to Run the Project
Clone the Repository
git clone https://github.com/yourusername/customer-churn-prediction.git
Navigate to Project Folder
cd customer-churn-prediction
Install Required Libraries
pip install -r requirements.txt
Run Jupyter Notebook
jupyter notebook
