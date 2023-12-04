# Predictive-Analytics-for-Term-Deposit-Subscription

This repository contains code, resources, and insights derived from predictive analytics on a Portuguese bank's marketing campaigns to forecast client subscription behaviour regarding term deposits.

# Business Problem Overview
The Portuguese bank has encountered a revenue decline due to reduced client deposits. The goal is to predict client subscription likelihood for term deposits to identify potential subscribers and focus marketing efforts accordingly.

# Key Insights from Exploratory Data Analysis (EDA)
**Insights**:
**Age Impact:** Clients above 60 years and below 30 years exhibit a higher probability of term deposit subscription.
**Loan & Housing:** Clients without a loan display a higher probability of subscribing.
**Duration Influence:** Subscribed clients often have a duration over 300.

**Model Performance Summary:**
Under Sampling: XGBOOST accuracy - 0.8748
Over Sampling: XGBOOST accuracy - 0.8738
SMOTE Technique: XGBOOST accuracy - 0.8950

# Targeted Customer Segments and Campaign Strategies
**Targeted Customers:**
**Age Range**: 30 – 60 years
**Education**: University, High School, Professional Courses
**Job**s: Admin, Blue-collar, Technician

# Recommended Campaign Strategies:
Customer Segments to Target: Those not targeted previously and successful customers from past campaigns.
Optimal Campaign Period: Plan campaigns from May through August for higher effectiveness.

# Implementation Recommendations
Utilize identified customer segments for tailored marketing strategies.
Focus on personalized campaigns during the recommended timeline for the specified customer segments.

# Further Suggestions:
Continual monitoring for evolving customer behaviour.
Refinement of targeting strategies based on ongoing data analysis.

# Repository Structure
Data: Contains the dataset used for analysis.
Notebooks: Jupyter notebooks for data exploration, preprocessing, modeling, and evaluation.
Documentation: Additional reports or analysis summaries.
Code: Scripts/modules for preprocessing, modeling, and evaluation.
Results: Visualizations, model performance metrics, and insights.
Resources: Supplementary materials, references, or external resources used during the project.
