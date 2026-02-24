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
1. Cleaned and prepared transaction data using Excel
2. Applied logical rules to detect suspicious activities
3. Used functions such as COUNTIF to aggregate fraud alerts
4. Built Pivot Tables to analyze user behavior and alert frequency
5. Created summary metrics to evaluate fraud trends.


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
1. High Alert Rate (49%) suggests either high fraud risk or overly sensitive rules
2. Multiple Accounts from Same IP is a major fraud indicator
3. Repeated Transactions indicate automated or scripted behavior
4. Multiple Failed Payments suggest card testing activity
5. Certain users triggered multiple alert types, indicating high-risk accounts

### Recommendations
1. Implement Automated Blocking to stop repeated transactions and failed attempts in real time
2. Enhance User Verification and add extra authentication for high-risk transactions
3. Limit Account Creation and restrict the number of accounts per IP address
4. Monitor High-Risk Users to focus on users triggering multiple alerts
5. Refine Detection Rules and adjust thresholds to reduce false positives
6. Track Fraud Trends by monitor alert rates weekly or monthly

### Skills Demonstrated
1. Data Cleaning & Preparation
2. Data Analysis using Excel
3. Fraud Detection Logic
4. Pivot Tables & Aggregation
5. Business Insight Generation
6. Risk Analysis

### Limitations
1. A small dataset (100 transactions) may not represent real-world behavior
2. A rule-based system may generate false positives
3. No machine learning model used
4. Limited historical data for trend analysis

### Future Improvements
1. Build a machine learning fraud detection model
2. Use larger real-world datasets
3. Integrate real-time monitoring dashboards (Power BI / Tableau)
4. Apply anomaly detection techniques
