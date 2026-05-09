Customer Churn Prediction using Machine Learning
Project Overview
This project predicts customer churn for a telecom company using machine learning techniques.

The goal is to identify customers likely to leave a service, enabling businesses to take proactive retention measures and reduce revenue loss.

Business Problem
Customer churn is a major challenge for subscription-based businesses.

Acquiring new customers is significantly more expensive than retaining existing ones.

This project leverages predictive analytics to detect high-risk customers early.

Dataset
Telco Customer Churn Dataset

Contains 7,000+ customer records including:

Customer demographics
Contract details
Monthly charges
Internet services
Payment methods
Churn status
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Jupyter Notebook
Machine Learning Models
Logistic Regression
Decision Tree
Random Forest
XGBoost
Evaluation Metrics
Accuracy
Precision
Recall
F1-score
ROC-AUC
Key Insights
Month-to-month contract users have higher churn probability
Higher monthly charges increase churn likelihood
Short-tenure customers are more likely to churn
Long-term contracts improve retention
Project Structure
customer-churn-prediction/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
Results
The best-performing model optimized recall, enabling better identification of at-risk customers.

This can help businesses:

Reduce churn
Improve customer retention
Increase lifetime value
Support data-driven decisions
How to Run
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook
Author
Anas Waqar
