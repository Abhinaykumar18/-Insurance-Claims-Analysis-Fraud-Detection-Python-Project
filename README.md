
# Insurance Claims Analysis & Fraud Detection | Python Project




## 📄 Project Overview
This project focuses on analyzing insurance claims data combined with customer demographics to derive insights about claim patterns and detect potential fraud cases. The objective was to clean, audit, and analyze the data, perform feature engineering, and prepare it for predictive modeling or business reporting.
## 📁 Dataset Description
The project uses two datasets:

* cust_demographics.csv — Contains customer profiles like gender, date of birth, state, contact details, and customer segment.

* claims.csv — Contains insurance claim details including claim date, incident cause, claim type, claim amount, police report status, total policy claims, and fraud flags.
## 📌 Problem Statement
Goal:
Perform data cleaning, auditing, and analysis to uncover insights about customer and claim profiles, handle missing values, detect fraud patterns, and prepare the data for  analytics and statistics
## 📚 Technologies & Tools Used
* Python 3.x

* Jupyter Notebook

* Libraries:
   pandas, numpy, matplotlib, seaborn, scipy.stats, datetime
## 📈 Key Steps & Methodology
* Data Loading & Merging:

  * Loaded both CSV files using pandas.

  * Merged datasets on Customer_ID to create a consolidated merged_df.

* Data Audit:

  * Verified data types against business expectations.

  * Converted DateOfBirth and claim_date to datetime type.

  * Identified columns with mismatches or inconsistent values (e.g. claim amounts as string).

* Missing Value Treatment:

  * Imputed missing numerical values with mean.

  * Imputed missing categorical values with mode.

  * Automated imputation using a for-loop based on data type.

* Feature Engineering:

  * Derived customer Age from DateOfBirth.

  * Created an alert_flag for injury claims not reported to the police.

  * Removed duplicate customer records, retaining only the most recent claim.

* Exploratory Data Analysis (EDA):

  * Summarized customer demographics.

  * Visualized distribution of claims by state, gender, and incident cause.

  * Analyzed fraud distribution across segments and claim types.
## 📊 Key Insights
* Detected higher fraud occurrence in certain customer segments and states.

* Found significant missing data patterns in police report fields for injury claims.

* Identified duplicated customer records requiring consolidation.

* Uncovered actionable insights for policy and risk management.
## 📑 Deliverables
* Cleaned and merged dataset.

* Data audit summary.

* Imputed missing values.

* Feature-engineered columns.

* EDA visualizations.
* Hypothesis Testing

* Business recommendations based on claims and fraud patterns.
