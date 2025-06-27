## loan_default
# Overview
Predicting the likelihood of a loan applicant defaulting is critical for risk management in the financial industry. This project uses machine learning techniques to build a predictive model that identifies potential loan defaulters based on borrower attributes and loan characteristics.
In this project, we built a decision tree, a random forest and three deep learning mordels using the keras sequential API on Tensorflow. The best performing model had a recall of 93% on test data.

# Data Understanding
The dataset contains 255,347 loan applications with 18 features spanning applicant demographics, financial history, and loan details. Below is a breakdown of the key attributes:

Numerical Features: Age, Income, LoanAmount, CreditScore, MonthsEmployed, NumCreditLines, InterestRate, LoanTerm, DTIRatio

Categorical Features: Education, EmploymentType, MaritalStatus, HasMortgage, HasDependents, LoanPurpose, HasCoSigner

Target Variable: Default (1 = Defaulted, 0 = Paid)

📊 Default Rate Summary (%):
The dataset is highly imbalanced, which is a critical consideration for modeling:

0 -   88.39%

1  -  11.61%

![Image Alt](https://github.com/user-attachments/assets/422aa212-89e7-4fe7-99e2-2a57438a9437)

# Business Understanding
For banks, loan defaults represent a major source of financial risk and reduced profitability. Accurately predicting the likelihood of default helps:

1. Protect the bank’s loan portfolio by reducing exposure to high-risk borrowers

2. Improve capital allocation through better credit scoring and risk-adjusted pricing

3. Support regulatory compliance by aligning with Basel III and other credit risk standards

4. Enhance customer targeting by offering appropriate loan products to low-risk clients

This project is designed to equip the bank with a data-driven decision-support tool that flags potentially default-prone applicants before loan disbursement, enabling more responsible lending and sustainable portfolio growth.



![image](https://github.com/user-attachments/assets/921f0bb5-3e9b-4824-bea8-6011550e1959)

![image](https://github.com/user-attachments/assets/7660bb79-ac3d-44b9-aeef-28250b90d6c6)

![image](https://github.com/user-attachments/assets/abb3dd54-f912-496e-b226-1515e408afd8)




