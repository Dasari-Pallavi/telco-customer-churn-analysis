\# Telco Customer Churn Analysis



An end-to-end data science project utilizing \*\*Python\*\* and \*\*Machine Learning\*\* to identify key drivers of telecom customer turnover and predict churn.



\## 📁 Repository Structure

\* `data/` - Holds raw source dataset (`WA\_Fn-UseC\_-Telco-Customer-Churn.csv`)

\* `notebooks/` - Contains the exploratory analysis and machine learning scripts

\* `requirements.txt` - Python package dependency configuration list



\## 📊 Key Business Insights \& Churn Drivers

Using a \*\*Scaled Logistic Regression Model\*\* (achieving \*\*80.55% Prediction Accuracy\*\*), we extracted the following top 4 customer retention drivers:



1\. \*\*Two-Year Contracts (`Contract\_Two year`: -1.32)\*\*: The absolute strongest anchor. Transitioning customers from month-to-month terms to 2-year terms drastically mitigates churn risk.

2\. \*\*Onboarding Tenure (`tenure`: -1.26)\*\*: High churn density occurs between months 0–10. Customers surviving the initial onboarding lifecycle exhibit strong long-term brand loyalty.

3\. \*\*Fiber Optic Infrastructure (`InternetService\_Fiber optic`: +1.13)\*\*: Fiber optic subscribers exhibit a disproportionately high risk of churning. This points toward potential product pricing friction or service delivery issues.

4\. \*\*Electronic Check Friction (`PaymentMethod\_Electronic check`: +0.38)\*\*: Manual monthly electronic checks drive higher churn rates compared to automated bank transfers.



\## 🛠️ How to run the analysis

1\. Install dependencies: `pip install -r requirements.txt`

2\. Run the environment: `python -m notebook`



