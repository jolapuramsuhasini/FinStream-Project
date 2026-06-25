FinStream: Digital Banking Feature Adoption & Churn Analysis
Locked — read-only blueprint

21-day · Data Analytics + AI
Project goal
FinStream, a mid-sized digital bank, recently launched three new premium features: Crypto-Wallet, Savings Goals, and Budgeting Tools. Despite high sign-up rates, monthly active usage is plateauing. The management needs to understand which features drive long-term retention and where users are dropping off in the product lifecycle to optimize their product roadmap.

Business problem
High initial feature friction and low cross-sell conversion are resulting in a 12% quarterly drop in active users for premium product tiers.

Key results you'll measure
Feature Adoption Rate (FAR)
Customer Churn Rate (CCR)
Average Product Usage Frequency
Customer Lifetime Value (CLV)
Dataset
Source: Synthesized Banking Product & Transaction Data (Kaggle/Mock)

SQL skills you'll practice
3 tasks in your blueprint

1.
Active User Segmentation
Identify Daily Active Users (DAU) and Monthly Active Users (MAU) per feature.
2.
Retention Cohort Analysis
Create a cohort table showing user retention 1, 2, and 3 months after their first feature interaction.
3.
Transaction High-Rollers
Rank top 10% of users by transaction volume and cross-reference with feature adoption.
Python skills you'll practice
3 tasks in your blueprint

1.
Exploratory Data Analysis (EDA)
Visualize distribution of session lengths and transaction frequencies across different user tiers.
2.
Correlation Analysis
Determine the statistical correlation between specific feature usage (e.g., Budgeting) and total deposit growth.
3.
Churn Prediction Preparation
Engineer features like 'Days since last login' and 'Monthly transaction delta' for predictive modeling.
Dashboard deliverable
AI deliverable
A Random Forest model implemented in Python to predict the likelihood of a user abandoning the app within the next 30 days based on their feature interaction patterns.

How you'll be evaluated
These are the criteria your mentor and AI evaluation use.

Accuracy of SQL cohort calculations
Successful handling of missing values and outliers in Python
Clarity and interactivity of the Power BI dashboard
Performance metrics (AUC/F1-Score) of the AI model
