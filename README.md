# Tata Data Analytics Job Simulation: AI-Powered Collections Strategy

## Project Overview
This project was completed as part of the Tata Data Analytics Virtual Internship through Forage. The objective was to help Geldium, a financial institution, transition from a reactive debt-collection process to a proactive, AI-driven strategy.

By leveraging data analytics and predictive modeling, I designed a system to identify at-risk customers early, allowing the bank to intervene with support before delinquency occurs.

---

## Task Breakdown

### Phase 1: Exploratory Data Analysis (EDA)
* Data Audit: Identified and resolved missing values in Income, Loan Balance, and Credit Score using statistical median imputation to maintain integrity.
* Risk Drivers: Analyzed correlation matrices to determine that Missed Payments and Credit Utilization are the strongest predictors of account delinquency.
* Visualizations: Generated correlation heatmaps and boxplots to visualize risk patterns across customer segments.

### Phase 2: Predictive Model Planning
* Model Selection: Proposed a Random Forest Classifier for its high accuracy and explainability in a financial context.
* Logic: The model generates a 0-1 risk probability score for every account on a daily basis.
* Evaluation Strategy: Focused on the F1-Score and AUC-ROC to balance catching high-risk cases without over-flagging stable customers.

### Phase 3: Business Storytelling
* Strategy: Recommended a 6-week SMS outreach pilot targeting the under-30 demographic with 2+ missed payments.
* Goal: Targeted a 10% reduction in 30-day delinquency rates while improving customer trust and retention.

### Phase 4: Implementation and Responsible AI
* Deployment: Outlined a roadmap for API integration and automated retraining cycles to manage model drift over time.
* Ethics: Integrated Bias Audits and Human-in-the-loop oversight to ensure compliance with financial regulations and fair treatment of all customers.

---

## Repository Contents
* Forage_TATA.pdf: Technical report on EDA and risk profiling.
* Predictive_Model_Plan.pdf: Strategic plan for AI deployment and model logic.
* Business_Summary_Report.pdf: Stakeholder-ready recommendation framework.
* Implementation_Roadmap.pdf: Final presentation on system maintenance, feedback loops, and ethics.

---

## Skills Demonstrated
* Technical: Python (Pandas, Seaborn, Matplotlib), Data Cleaning, Statistical Imputation, Correlation Analysis.
* Strategic: Predictive Modeling Logic, SMART Goal Setting, Business Reporting, Data Storytelling.
* Ethical: Responsible AI Design, Bias Detection, Regulatory Compliance, Human-in-the-loop Systems.
