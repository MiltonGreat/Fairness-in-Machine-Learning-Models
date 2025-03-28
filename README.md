# Fairness in Machine Learning Models

The respository shows projects that applying fairness in machine learning for financial scenarios, especially in credit risk modeling, lending, and fraud detection. Here are some datasets where I simulated bias detection, fairness auditing, and mitigation techniques in financial decision-making.

### 1. German Credit Data (Credit Risk & Fairness)

**Dataset:** German Credit Data

**Description:** This dataset contains 1,000 credit applicants' financial and demographic details, including credit history, loan purpose, and employment status. The target variable is whether an applicant has "Good" or "Bad" credit, making it useful for both credit risk modeling and fairness analysis.

**What I Did in the Project:**

- **Bias Detection in Credit Approvals:** Analyzed approval rates across gender and age groups to identify disparities.
- **Fairness Metrics Computation:** Used Aequitas, Fairlearn, and AIF360 to calculate Demographic Parity, Equalized Odds, and Disparate Impact.
- **Model Bias Testing:** Built logistic regression and decision tree models to predict credit risk and evaluated bias in model predictions.
- **Bias Mitigation Techniques:** Applied reweighing, adversarial debiasing, and reject inference to correct unfair model decisions.

### 2. Home Credit Default Risk (Fair Lending & Bias in Credit Scoring)

**Dataset:** Home Credit Default Risk

**Description:** This real-world financial dataset contains loan applications, borrower demographics, and credit history information. Certain demographic features, such as gender, income type, and family status, may introduce bias in lending decisions.

**What I Did in the Project:**

- **Bias in Credit Scoring:** Identified whether women, single parents, or low-income groups faced higher rejection rates.
- **Loan Approval Disparities:** Analyzed default rates across socioeconomic groups to determine if models treated them fairly.
- **Algorithmic Bias Analysis:** Compared ML models' performance across different demographic subgroups to check for bias.
- **Explainability in Credit Decisions:** Used SHAP and LIME to identify which features most contributed to biased outcomes.

### 3. Lending Club Loan Data (Fairness in Loan Approvals)

**Dataset:** Lending Club Loan Data

**Description:** This dataset contains loan status, credit scores, and borrower details, making it useful for analyzing fairness in loan approvals. Features like income, job title, and loan purpose could introduce bias in lending decisions.

**What I Did in the Project:**

- **Bias in Lending Decisions:** Investigated whether certain income groups received higher interest rates or more frequent rejections.
- **Debt-to-Income Impact on Loan Decisions:** Examined whether minority groups faced stricter lending rules.
- **Regulatory Compliance Simulation:** Applied Fair Lending Laws (ECOA) and fairness auditing techniques.
- **Fair Model Adjustments:** Implemented FairBoost and equalized odds post-processing to improve fairness in loan approvals.

### 4. Give Me Some Credit (Bias in Credit Scores)

**Dataset:** Give Me Some Credit

**Description:** This dataset focuses on personal finance and loan approvals, where variables like age, income, and employment history affect risk assessment. It is useful for exploring bias in credit scoring models.

### What I Did in the Project:

- **Age Discrimination in Credit Scoring:** Investigated whether older applicants received lower scores unfairly.
- **Race/Gender Fairness Simulation:** Simulated race-based disparities by grouping income and geography data.
- **Comparison of Traditional vs. ML Models:** Evaluated if machine learning models introduced more bias than traditional scoring methods.

### 5. Brazilian E-Commerce Public Dataset (Bias in Credit Approvals for Online Lending)

**Dataset:** Brazilian E-Commerce Dataset

**Description:** This dataset contains customer demographic data, credit card payments, and transaction history, making it useful for analyzing bias in online credit approvals.

**What I Did in the Project:**

- **Geographical Bias in Credit Decisions:** Checked if rural applicants were less likely to be approved compared to urban applicants.
- **Loan Amount Disparities:** Investigated whether certain customer segments received lower loan amounts or worse repayment terms.
- **Bias in Payment Defaults:** Analyzed whether income level affected how defaults were classified.
