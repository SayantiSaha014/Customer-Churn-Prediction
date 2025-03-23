
<h1 align="center">  📊Customer Churn Prediction📊</h1>
<div align="center">
  <img src="Customer Churn Prediction Logo.jpeg" width='300'>
</div>



## 📃**Introduction**

As we know , Customer churn is a critical metric that can significantly impact a company's bottom line. In the "Customer Churn Prediction" project, we leverage machine learning with Python to predict potential churn, enabling proactive strategies for customer retention. The predictive model, built using Random Forest algorithm .

The insights derived from the model are seamlessly integrated into a dynamic Power BI dashboard. This interactive dashboard provides stakeholders with a comprehensive view of churn trends, key drivers, and actionable insights. With intuitive visualizations and filtering options, users can explore the data in depth, allowing for informed decision-making and targeted retention strategies.

This project demonstrates the effective use of machine learning in solving real-world business challenges and highlights the importance of data visualization in translating complex insights into strategic actions.

## **Project Type**

PowerBi Dashboard, using Python and Machine Learning for modeling


## 🎬**Video WalkThrough of the project**



## 📂 **About the Dataset**

The dataset `Telco-Customer-Churn.csv` includes comprehensive collection of historical customer information, designed to help identify patterns and key factors influencing customer churn.

## 📜 **Link of the Dataset**
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

**Rows**

- Each Row Represents a Single Customer: 7032 numbers

Every row corresponds to an individual customer with their unique customerID and encapsulates their personal, subscription, and service usage data. This structure allows us to analyze customer behavior and identify patterns that lead to churn.

**Columns**

- The dataset comprises Columns: 21 

Named
  - CustomerID
  - Gender
  - SeniorCitizen
  - Partner
  - Dependents
  - Tenure
  - PhoneService
  - MultipleLines
  - InternetService
  - OnlineSecurity
  - OnlineBackup
  - DeviceProtection
  - TechSupport
  - StreamingTV
  - StreamingMovies
  - Contract
  - PaperlessBilling
  - PaymentMethod
  - MonthlyCharges
  - TotalCharges
  - Churn

## 🚀**Installation and Setup**

1. **Clone the repository:**
  ```bash
  git clone (https://github.com/SayantiSaha014/Customer-Churn-Prediction.git)
```

2. **Install required dependencies:**

  ```bash
  pip install -r requirements.txt
  ```


## 📂 **About the Design of the project**


1.	Data Collection: Kaggle dataset (CSV format).
2.	Data Preprocessing:
	- Handling missing values, encoding categorical features.
  	- Normalizing numerical values for better model performance.
3.	Modeling : Random Forest Classifier 
4.	Evaluation:
	- Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
  	- Plotted a confusion matrix to analyze prediction performance.
5.	Power BI Integration : Exported results as CSV for visualization.

##  **Model Evaluation**

The model performance is evaluated using the following metrics like Accuracy , Precision , Recall , F1-score , ROC-AUC Score.
The final Accuracy is 80% and ROC-AUC Score is 84% .


## 🔎**Business Insights & Recommendations:**

	- High-risk groups (month-to-month contracts, high customer service calls) need retention strategies.

	- Offering discounts or contract renewals can reduce churn.

	- Improving customer service quality and engagement can help retain customers.

 
