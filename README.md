# FRAUD-DETECTION-RULES-REPORTING-SYSTEM

### Executive Summary
In this project, I developed a rule-based fraud detection system to identify suspicious activities in transaction data. Using Excel, I analyzed user behavior and implemented detection rules based on transaction patterns, thresholds, and anomalies.

### Problem Statement
Fraudulent transactions can lead to significant financial losses and damage user trust. This project aims to identify suspicious transaction patterns and design rules that can automatically flag potential fraud.
This analysis answers key questions such as:
What transaction patterns indicate potential fraud?
Which users trigger the highest number of fraud alerts?
What types of fraud occur most frequently?

### Methodology
Cleaned and prepared transaction data using Excel
Applied logical rules to detect suspicious activities
Used functions such as COUNTIF to aggregate fraud alerts
Built Pivot Tables to analyze user behavior and alert frequency
Created summary metrics to evaluate fraud trends.

### Fraud Detection Rules Implemented

1. Failed Payment Threshold
Flag users with 2 or more failed transactions within 24 hours
Helps detect card testing or payment failures

2. Large Transaction Deviation
Flag transactions above 50% of a user’s average transaction value
Detects abnormal spending behavior

3. Repeated Transactions
Flag repeated transactions within a short time window (e.g., 15 minutes)
Indicates potential automated or bot activity

4. Unusual Transaction Time
Flag transactions during off-hours (late night / early morning)
Identifies abnormal usage patterns

5. Multiple Accounts from Same IP
Flag multiple accounts registered from the same IP
Detects fake or duplicate account creation

6. Suspicious Payment Methods
Flag excessive use of prepaid cards or multiple failed attempts
Indicates potential fraudulent payment methods

7. Multiple Withdrawals
Flag more than 2 withdrawals within 24 hours
Detects rapid fund extraction behavior

### Key Insights
High Alert Rate (49%) suggests either high fraud risk or overly sensitive rules
Multiple Accounts from Same IP is a major fraud indicator
Repeated Transactions indicate automated or scripted behavior
Multiple Failed Payments suggest card testing activity
Certain users triggered multiple alert types, indicating high-risk accounts

### Recommendations
Implement Automated Blocking to stop repeated transactions and failed attempts in real time

Enhance User Verification and add extra authentication for high-risk transactions

Limit Account Creation and restrict the number of accounts per IP address

Monitor High-Risk Users to focus on users triggering multiple alerts

Refine Detection Rules and adjust thresholds to reduce false positives

Track Fraud Trends by monitor alert rates weekly or monthly

### Skills Demonstrated
Data Cleaning & Preparation
Data Analysis using Excel
Fraud Detection Logic
Pivot Tables & Aggregation
Business Insight Generation
Risk Analysis

### Limitations
A small dataset (100 transactions) may not represent real-world behavior
A rule-based system may generate false positives
No machine learning model used
Limited historical data for trend analysis

### Future Improvements
Build a machine learning fraud detection model
Use larger real-world datasets
Integrate real-time monitoring dashboards (Power BI / Tableau)
Apply anomaly detection techniques
