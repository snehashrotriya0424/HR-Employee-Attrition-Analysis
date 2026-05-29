# HR Analytics: Employee Attrition Analysis

##  Project Overview
This project analyzes employee attrition using Python. The goal is to identify trends in why employees leave a company by examining factors like monthly income, age, and job satisfaction. 

*Note: To ensure strict data privacy and security, this analysis uses a synthetically generated dataset.*

##  Tools Used
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization), NumPy (Data Generation)

##  Key Findings & Insights
Based on the exploratory data analysis, we uncovered the following trends:
1. **Income Disparity:** Employees who left the company ("Yes" in Attrition) generally had a lower median monthly income compared to those who stayed.
2. **Job Satisfaction:** Lower job satisfaction scores (1 and 2) strongly correlated with higher attrition rates. 
3. **Retention Strategy:** To reduce the 16% baseline turnover rate, HR should focus on compensation reviews for underpaid staff and investigate departments with historically low satisfaction scores.

##  How to Run
1. Clone this repository.
2. Ensure you have `pandas`, `matplotlib`, and `seaborn` installed.
3. Run `attrition_analysis.py` to view the console metrics and generate the `hr_attrition_dashboard.png` visualization.
