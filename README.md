📊 Project Overview: Customer Credit Consumption Prediction
🧾 Objective:
To build a machine learning model that predicts the average credit card spend of customers for the next three months, based on their demographic data, financial behavior, and historical transaction patterns. The model helps in better customer profiling and supports targeted financial offerings by banking institutions.

🏦 Business Context:
In the credit card industry, understanding customer-level spending behavior is crucial for strategic decisions like personalized offers, risk assessment, and customer retention. This project aims to analyze customer data to uncover patterns in credit card consumption and forecast future spending for improved decision-making.

📁 Dataset:
The project uses three datasets:

Customer Demographics – Basic profile details like age, income, region, banking tenure, etc.

Behavioral Data – Credit/debit card transactions, loan history, asset holdings, and account activity over three months (April to June).

Credit Consumption – Target variable indicating average credit card consumption over the upcoming three months (July to September); partially missing and used for prediction.

🔧 Methodology:
Data Preprocessing: Merged datasets, handled missing values, outliers, and inconsistent data.

Feature Engineering: Created meaningful derived variables to enhance model learning (e.g., transaction frequency, credit utilization).

EDA: Explored key trends and correlations influencing credit card spending.

Modeling: Built and tuned regression models (e.g., Linear Regression, Decision Tree, etc.).

Evaluation: Assessed model performance using RMSPE (Root Mean Square Percentage Error).

Prediction: Generated credit consumption predictions for customers with missing target values.

🧠 Skills & Tools Used:
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Techniques: Data Cleaning, Feature Engineering, Regression Modeling, Model Evaluation, Predictive Analytics

✅ Outcome:
Achieved a predictive model capable of estimating future credit card spending with minimized error. The insights derived enable banks to personalize services and refine their customer engagement strategies.
