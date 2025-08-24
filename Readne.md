LendingClub Loan Default Risk Analysis
📌 Project Overview

This project explores the LendingClub loan dataset to understand borrower behavior, repayment patterns, and risk factors behind loan defaults.
The notebook covers data wrangling (cleaning & preprocessing) and exploratory data analysis (EDA) with visualizations and insights.

The goal is to identify the features most strongly associated with loan default and provide data-driven recommendations for lenders.

📂 Repository Structure
├── data_wrangling.ipynb   # Jupyter notebook with EDA
├── README.md              # Project documentation
└── data/                 

🛠️ Tools & Libraries

Python

Pandas

NumPy

Matplotlib / Seaborn


📊 Exploratory Data Analysis (EDA)

Key insights discovered:

Target Variable Distribution

~83% loans repaid, ~17% defaulted → dataset is imbalanced.

Loan Amount

Most loans are $10k–15k.

Defaults more common among higher-value loans.

Interest Rate

Strong correlation with default.

Borrowers with >15% interest rates are much more likely to default.

Loan Grade / Sub-Grade

Grades A–B are safer investments.

Grades E–G have high default risk despite higher interest.

Income

Low-income borrowers riskier, but high income ≠ guaranteed repayment.

Other Features

Employment length: little effect.

Debt-to-Income (DTI): higher DTI → higher risk.

Loan purpose: small business loans riskier.

Application type: joint applications slightly safer.

💡 Recommendations

Focus investments on A–C grade loans to balance risk & return.

Pay closer attention to high loan amounts & high interest loans.

Use income in combination with other features (grade, DTI, loan size) for risk assessment.

Avoid over-reliance on weak predictors (employment length, home ownership).

🚀 Next Steps

Build a predictive machine learning model for loan default classification.

Perform feature engineering (e.g., interaction terms, credit utilization ratios).

Use imbalanced learning techniques (SMOTE, class weights) to handle target imbalance.

📈 Project Value

This project demonstrates skills in:

Data wrangling & preprocessing

Exploratory data analysis (EDA)

Risk factor identification in credit datasets

Clear business-oriented recommendations

✍️ Author: Mukul Negi
📌 Dataset: LendingClub loan dataset (available on Kaggle
)