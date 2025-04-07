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

- **[Age Discrimination in Credit Scoring:](https://github.com/MiltonGreat/Age-Discrimination.git)** Investigated whether older applicants received lower scores unfairly.
- **[Race/Gender Fairness Simulation:](https://github.com/MiltonGreat/Fairness-Simulation.git)** Simulated race-based disparities by grouping income and geography data.
- **[Comparison of Traditional vs. ML Models:](https://github.com/MiltonGreat/Comparison-of-Traditional-vs.-ML-Models.git)** Evaluated if machine learning models introduced more bias than traditional scoring methods.

### 3. Loan Application Data (Loan Eligibility & Fairness Analysis)

**Dataset:** Loan Application Data

**Description:** This dataset contains applicant-level financial and demographic information typically used to determine loan eligibility.

**What I Did in the Project:**

- **[Fairness Audit with Aequitas and Fairlearn:](https://github.com/MiltonGreat/Fairness-Audit-with-Aequitas-and-Fairlearn.git)** Evaluated fairness of prediction models using Demographic Parity, Equal Opportunity, and Disparate Impact metrics. Audited results with Aequitas fairness reports on gender.
- **[Bias Detection in Approvals:](https://github.com/MiltonGreat/Bias-Detection-in-Approvals.git)** Performed group-wise analysis of approval rates by gender, marital status, and property area.
