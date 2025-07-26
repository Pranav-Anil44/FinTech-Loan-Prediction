# FinTech-Loan-Prediction
Loan approval prediction using logistic regression on fintech data
📊 FinTech Loan Approval Prediction – Logistic Regression
🚀 Project Overview
This project aims to predict whether a loan application will be approved based on customer financial and loan history information. The work demonstrates a complete data science pipeline including preprocessing, feature engineering, model evaluation, and insights — making it ideal for recruiters looking to evaluate both technical and problem-solving skills.

🧠 Objective
To build a binary classification model using Logistic Regression to predict loan approval status (Loan_Approved) for fintech customers using a realistic but synthetic dataset.

📁 Dataset
File Used: messy_fintech_loan_dataset.csv

Total Rows Initially: 192

Expanded to: 1000 (to reduce underfitting and improve generalization)

Target Variable: Loan_Approved

⚙️ Workflow Summary
1. Data Preprocessing
Removed outliers using IQR-based filtering for numerical columns.

Handled missing values.

Performed feature scaling using StandardScaler.

Applied one-hot encoding for categorical variable Loan_Type.

2. Feature Engineering
Added meaningful derived features to enhance model performance:

✅ Credit_Utilization: Ratio of Transaction_Amount to Monthly_Income

✅ CreditScore_per_History: Ratio of Credit_Score to Loan_History_Length

3. Model Building
Algorithm: Logistic Regression (sklearn)

Train/Test Split: 80/20

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

ROC AUC Score

📈 Model Performance (on 1000 rows)
Metric	Value
Accuracy	~56.5%
Precision	~57.9%
Recall	~44.4%
F1 Score	~50.2%
ROC AUC Score	0.653 ✅ (after feature engineering)

🧠 Key Learnings
Understood the importance of data cleaning (outlier removal, missing values).

Learned to evaluate classification models beyond accuracy using F1 and ROC AUC.

Implemented feature engineering to boost model relevance and interpretability.

Managed low data volume challenges through synthetic data expansion.

Gained hands-on experience with Git and project deployment to GitHub.

📚 Technologies Used
Pandas, NumPy – data manipulation

Matplotlib, Seaborn – visualization

Scikit-learn – modeling and metrics

Git, GitHub – version control and hosting

✅ Project Status
✅ Completed for educational & portfolio showcasing purposes

🛠️ Can be improved using advanced models (Random Forest, XGBoost, etc.)

🚀 Future Work: Try with real-world datasets and ensemble techniques

🔗 GitHub Repo
📂 FinTech Loan Prediction on GitHub

🙌 Acknowledgment
This project was a part of my data science learning journey, demonstrating how a structured approach — even on limited data — can lead to valuable insights and better understanding of ML pipelines.

Pranav A Kumar
Technology Enthusiast | IT Professional with a Passion for Data & Problem-Solving
🔗 https://www.linkedin.com/in/pranav-a-kumar-2a39b4358/
