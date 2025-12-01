📊 Customer Churn Prediction & Retention Analytics

A Machine Learning project built to predict customer churn and identify key factors influencing customer retention using the Telco Customer Churn Dataset.
This project applies classification models, compares performance, visualizes feature importance, and generates churn insights that can be used for business decision-making.

🚀 Project Overview

Customer churn occurs when customers stop using a product or service.
The goal is to predict which customers are likely to churn, analyze why, and determine what actions can reduce churn.

This project includes:

Component	Status
Data Cleaning & Preprocessing	✔ Completed
Exploratory Data Analysis (EDA)	✔ Done
Model Training: Logistic Regression & Random Forest	✔ Done
Evaluation Metrics	✔ Added
Feature Importance Visualization	✔ Plotted
Insights + Summary	✔ Documented
📂 Dataset

File Used: WA_Fn-UseC_-Telco-Customer-Churn.csv
Rows: ~7043
Target Variable: Churn (1 = customer left, 0 = customer retained)

🛠 Tech Stack & Libraries
Category	Tools
Language	Python
Data Handling	Pandas, NumPy
ML Models	Scikit-Learn
Visualization	Matplotlib, Seaborn
Evaluation	Accuracy, F1-Score, Recall, ROC-AUC
🧠 Approach

Data Cleaning + Missing Value Handling

Categorical Encoding (Label Encoding)

Train-Test Split

Model Training:
🔹 Logistic Regression
🔹 Random Forest Classifier

Evaluation & Comparison

Feature Importance Ranking

Insights + Interpretation for churn reduction

📈 Model Performance
Model	Performance
Logistic Regression	(your accuracy here)
Random Forest	(your accuracy + AUC here)

Random Forest typically performs better due to non-linear relationships in customer behavior.

🔥 Feature Importance (Top Predictors)
Rank	Feature
1	Tenure
2	MonthlyCharges / TotalCharges
3	Contract Type
4	Internet Service
5	Payment Method

(Replace with exact top 10 from your feature importance graph)

📌 Insights & Business Value
• Long-term customers (higher tenure) churn significantly less.
• Month-to-month contracts have highest churn risk.
• Higher monthly charges correlate with churn.
• Auto-payment & yearly contract customers stay longer.

🏁 Conclusion

This project successfully:

✔ Predicts the likelihood of customer churn
✔ Identifies high-risk customer segments
✔ Highlights business strategies for retention
✔ Provides feature-level explainability using visual insights

📎 Future Scope

🔹 Deploy model as an API/Flask/FastAPI service
🔹 Add dashboard using Streamlit/Power BI
🔹 Build customer retention recommendation engine

⭐ If you found this useful — star the repository!