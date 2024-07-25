Gameflix Cohort Analysis Project
Overview
This project involves analyzing customer retention and lifetime value for Gameflix, an OTT platform specializing in live sports streaming services. The analysis is conducted using cohort analysis to evaluate customer engagement over time. The insights derived from this analysis will help Gameflix understand customer behavior and improve retention strategies.

Project Background
Despite offering a diverse range of sports events, Gameflix has been facing ongoing difficulties in retaining customers in the Indian market. The customer retention has been a persistent challenge for the past two years. This project aims to address this issue by providing a detailed cohort analysis and customer lifetime value (CLV) calculation.

Data Sources
The analysis is based on the following datasets:

USER_REGISTRATION: Contains user demographics and sign-up information.
PROMOTIONAL_PLAN: Details of promotional offers.
ORDER: Information about user subscriptions and orders.
Analysis Steps
Task 1: Data Preparation
Import Data: Import the provided datasets into separate sheets in Excel.
Check Data Quality: Ensure there are no duplicates and the data is consistent.
Format Dates: Ensure all date columns are formatted consistently (e.g., DD/MM/YYYY).
Combine Data: Create a unified data frame by combining necessary columns from each dataset.
Task 2: Creating Customer Cohorts & Analyzing Retention
What is Cohort Analysis?
Cohort analysis groups customers based on shared characteristics, typically their sign-up date, and tracks their behavior over time.

Steps to Create Cohorts
Identify Cohorts: Group customers based on their subscription start date.
Calculate Retention Rates: For each cohort, count the number of active users in each subsequent month.
Visualize Retention Trends: Create a heatmap to visualize retention rates over time.
Task 3: Customer Lifetime Value (CLV)
Formula for CLV

Steps to Calculate CLV
Calculate Total Cohort Revenue: Sum all monthly payments for each cohort.
Calculate Average Revenue Per Customer: Divide the total cohort revenue by the number of customers in the cohort.
Calculate CLV: Use the formula provided to calculate the CLV for each cohort.
Task 4: Analyzing Promotional Impact
Combine User Data with Orders and Promotions: Use VLOOKUP or INDEX-MATCH to combine user data with their orders and promotional plans.
Pivot Table: Create a pivot table to analyze the impact of different promotional plans on retention and CLV.
Visualize Promotional Impact: Create charts to visualize the retention rates and CLV for users under different promotional plans.
Key Findings
Overall Retention Rates: Insights into how retention rates vary across different cohorts.
Most Valuable Cohorts: Identification of high-value customer segments.
Effective Promotional Strategies: Analysis of which promotional plans are most effective in retaining customers.
Recommendations
Personalized Content Recommendations: Utilize user viewing history to suggest relevant sports events.
Targeted Promotions: Design cohort-specific promotional offers.
Improve Onboarding: Enhance the new user experience to encourage early engagement.
Loyalty Programs: Implement rewards for long-term subscribers.
Content Diversity: Ensure a balanced offering of popular and niche sports.
Technical Improvements: Address any streaming quality or user interface issues.
Feedback Loop: Regularly collect and act on user feedback.
Re-engagement Campaigns: Develop strategies to win back churned customers.
Future Work
In the future, I plan to extend this analysis using:

Python: For more advanced data analysis and visualization.
SQL: For efficient data querying and manipulation.
Power BI: For creating interactive dashboards and reports.
Acknowledgements
This project was completed as part of a Skill Cred micro internship under the mentorship of Mohit Malani Sir. I would like to thank him for his guidance and support throughout the project.

Conclusion
Through this concise summary, Gameflix will be able to assess exactly how a group of their subscribers behaved over their time with the platform and what measures can be taken to increase retention rates.

Repository Structure
data/: Contains the raw datasets used for analysis.
notebooks/: Jupyter notebooks with the analysis code.
reports/: Generated reports and visualizations.
README.md: Project overview and documentation.
