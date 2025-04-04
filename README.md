# Fairness in Machine Learning Models

The respository shows projects that applying fairness in machine learning for financial scenarios, especially in credit risk modeling, lending, and fraud detection. Here are some datasets where I simulated bias detection, fairness auditing, and mitigation techniques in financial decision-making.

### 1. German Credit Data (Credit Risk & Fairness)

**Dataset:** German Credit Data

**Description:** This dataset contains 1,000 credit applicants' financial and demographic details, including credit history, loan purpose, and employment status. The target variable is whether an applicant has "Good" or "Bad" credit, making it useful for both credit risk modeling and fairness analysis.

**What I Did in the Project:**

- **[Bias Detection in Credit Approvals:](https://github.com/MiltonGreat/Bias-Detection.git)** Analyzed approval rates across gender and age groups to identify disparities.
- **[Fairness Metrics Computation:](https://github.com/MiltonGreat/Credit-Risk-Fairness-Analysis.git)** Audited model using Aequitas and Fairlearn to calculate Demographic Parity, Equalized Odds, and Disparate Impact.
- **[Model Bias Testing:](https://github.com/MiltonGreat/Model-Bias-Testing.git)** Built logistic regression and decision tree models to predict credit risk and evaluated bias in model predictions.
- **[Bias Mitigation Techniques:](https://github.com/MiltonGreat/Bias-Mitigation-Techniques.git)** Applied reweighing, adversarial debiasing, and reject inference to correct unfair model decisions.

### 2. Give Me Some Credit (Bias in Credit Scores)

**Dataset:** Give Me Some Credit

**Description:** This dataset focuses on personal finance and loan approvals, where variables like age, income, and employment history affect risk assessment. It is useful for exploring bias in credit scoring models.
**What I Did in the Project:**

- **Age Discrimination in Credit Scoring:** Investigated whether older applicants received lower scores unfairly.
- **Race/Gender Fairness Simulation:** Simulated race-based disparities by grouping income and geography data.
- **Comparison of Traditional vs. ML Models:** Evaluated if machine learning models introduced more bias than traditional scoring methods.

### 3. Brazilian E-Commerce Public Dataset (Bias in Credit Approvals for Online Lending)

**Dataset:** Brazilian E-Commerce Dataset

**Description:** This dataset contains customer demographic data, credit card payments, and transaction history, making it useful for analyzing bias in online credit approvals.

**What I Did in the Project:**

- **Geographical Bias in Credit Decisions:** Checked if rural applicants were less likely to be approved compared to urban applicants.
- **Loan Amount Disparities:** Investigated whether certain customer segments received lower loan amounts or worse repayment terms.
- **Bias in Payment Defaults:** Analyzed whether income level affected how defaults were classified.
