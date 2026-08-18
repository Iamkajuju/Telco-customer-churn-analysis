# Telco-customer-churn-analysis
## Table of Content
  - [Description](#description)
  - [Project Aim](#project-aim)
  - [Business questions](#business-questions)
  - [Aim of the analysis](#aim-of-the-analysis)
  - [Processes](#processes)
  - [Insights](#insights)
  - [Recommendations](#recommendations)
  - [How to use the dashboard](#how-to-use-the-dashboard)
    
### Description
This project offers an opportunity to gain hands on experience in analyzing data using excel including data cleaning, exploratory data analysis (EDA), PivotTables, KPI development, and dashboard creation. I used a Telco customer dataset to explore patterns in customer behavior, contracts, billing, demographics, and service usage that may be associated with churn.

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

<img width="1864" height="628" alt="Screenshot 2026-08-18 091950" src="https://github.com/user-attachments/assets/5e68a641-5bb4-4e10-a5e2-089b6904741e" />



### Project Aim
The aim of this project is to analyze customer churn and identify customer characteristics and service factors associated with higher churn rates.
The objective of this project is to answer the following question:
- Which customer characteristics, contract types, billing patterns, and services are associated with higher customer churn?

### Business questions
I identified several pressing challenges related to customer retention, presented in bullet points for clarity:
- High churn rates: Many customers are leaving the company services
- Limited insights: Lack of actionable insights into customer satisfaction
- Lack of trend identification: Identifying patterns affecting customers retention is difficult

### Aim of the analysis
The primary objectives of this analysis are as follows:
- Clean and prepare customer data for analysis
- Data analysis: Analyze customer data to identify patterns associated with churn and compare churn across customer demographics, contracts, services, and billing behavior
- Build an interactive Excel dashboard for business decision-making

### Processes
Step 1: Data Preparation & Cleaning
  Tools: Microsoft Excel — Tables, Filters, Formulas, Conditional Formatting, Box & Whisker Plot

Activities:
- Reviewed the dataset structure and variables.
- Created a separate working dataset from the raw data.
- Checked for duplicate customer records and validated Customer ID uniqueness.
- Checked for blank/missing values.
- Investigated blank values in Total Charges and found that they were associated with customers with zero tenure.
- Checked data types to ensure numerical and categorical variables were stored appropriately.
- Checked categorical variables for consistency and standardization.
- Examined numerical variables (Tenure, Monthly Charges, and Total Charges) for potential outliers using box-and-whisker plots.
- Removed invalid records where necessary.
- Confirmed that the cleaned dataset contained no remaining duplicates or blanks requiring correction.

 Step 2: Exploratory Data Analysis (EDA)
   Tools: Microsoft Excel — PivotTables, Formulas

Activities:
- Created PivotTables to examine customer churn across demographic characteristics, customer and billing characteristics and different additional services
- Calculated churn rates for the different customer categories using the number of customers with Churn = Yes relative to the total customers in each category.
- Compared churn rates across categories to identify patterns and potential churn drivers.
- Identified the customer segments and services associated with higher churn.

 Step 3: Data Visualization
   Tools: Microsoft Excel — Charts, KPIs, Dashboard

Activities:
- Selected appropriate chart types based on the findings from the EDA.
- Created charts to visualize the most significant churn patterns.
- Created KPI cards for: Total Customers, Churned Customers, Overall Churn Rate
- Designed an Excel dashboard to bring the key findings together.

### Insights
- Contract Type and Customer Retention: Month-to-month customers show higher churn compared with customers on one- and two-year contracts. This suggests that customers with less contractual commitment may be more likely to leave, highlighting contract duration as an important factor to consider when developing retention strategies.
- Early Tenure and Churn Risk: Customers with one year or less tenure experience higher churn than customers who have been with the company longer. This indicates that the early stage of the customer relationship may represent a particularly vulnerable period, suggesting that stronger onboarding and early engagement strategies could help improve retention.
- Monthly Charges and Churn: Customers in the higher monthly-charge groups show higher churn rates than customers paying lower monthly charges. This pattern suggests that pricing or perceived value may influence customer retention, particularly among customers facing higher monthly bills.
- Payment Method and Churn: Customers using electronic checks have a higher churn rate than customers using other payment methods. This identifies electronic-check users as a higher-risk customer segment and suggests that further investigation into their payment experience or customer characteristics may be valuable.
- Fiber Optic Service and Churn: Fiber optic customers have the highest churn rate among the internet-service categories analyzed. This indicates that fiber customers may be experiencing factors that contribute to lower retention, such as pricing, service expectations, or customer experience, and warrants further investigation.
- Additional Services and Retention: Customers without Tech Support, Online Security, Online Backup, and Device Protection generally show higher churn rates than customers subscribed to these services. This suggests that additional support and security services may be associated with stronger customer retention and could potentially contribute to customers' perceived value of the service.
- Customer Age and Churn: Senior citizens have a higher churn rate than non-senior customers. This identifies senior customers as a segment that may require closer attention when developing customer support and retention strategies.
- Partner Status and Churn: Customers without partners have a higher churn rate than customers with partners. This suggests that household or customer circumstances may be associated with differences in retention behavior.
- Dependents and Churn: Customers without dependents show higher churn than customers with dependents. This indicates that household characteristics may be associated with different customer retention patterns.
- Gender and Churn: Churn rates for male and female customers are very similar. This suggests that gender is not a strong differentiating factor in this dataset and therefore may be less useful for prioritizing churn-reduction efforts.

### Recommendations
- Strengthen Retention During the Early Customer Lifecycle: Since customers with one year or less tenure show higher churn rates, the business could introduce stronger onboarding and early-stage engagement strategies. Regular check-ins, targeted support, and introductory offers could be considered to help new customers establish longer-term relationships with the company.
- Encourage Longer-Term Contracts: Month-to-month customers have substantially higher churn than customers on one- and two-year contracts. The business could encourage customers to move toward longer-term contracts through incentives, loyalty benefits, or pricing options that make longer commitments more attractive.
- Review Pricing and Value for High-Charge Customers: Higher monthly-charge groups show higher churn rates. The business could review the pricing and perceived value of higher-cost plans and consider targeted offers, plan adjustments, or loyalty incentives for customers with higher monthly bills.
- Investigate the Electronic Check Customer Segment: Electronic check users have a higher churn rate than customers using other payment methods. The business could investigate whether this group experiences differences in payment processes, customer characteristics, or service usage and consider encouraging alternative payment methods where appropriate.
- Investigate the High Churn Among Fiber Optic Customers: Fiber optic customers have the highest churn rate among the internet-service categories. The business should investigate potential factors behind this pattern, such as pricing, service quality, customer expectations, or support experience, before deciding on a specific retention strategy.
- Promote Value-Adding Support and Security Services: Customers without Tech Support, Online Security, Online Backup, and Device Protection generally show higher churn. The business could consider targeted bundles, trials, or educational campaigns that communicate the benefits of these services to customers who are not currently subscribed.
- Develop Targeted Retention Strategies for Higher-Risk Demographic Groups: Senior citizens, customers without partners, and customers without dependents show higher churn rates. Rather than applying a single strategy to all customers, the business could investigate the needs of these segments and develop more targeted engagement or support initiatives.
- Avoid Using Gender as a Primary Churn Target: Since male and female customers have similar churn rates, gender does not appear to be a meaningful differentiator in this analysis. Retention resources could therefore be prioritized toward factors showing larger differences in churn, such as contract type, tenure, monthly charges, and services.

### How to use the dashboard
Step 1: Download the dashboard
- Download the Customer_churn.xlsx file from the folder in this repository.
 - [Download Customer churn Workbook](Customer_churn.xlsx)

Step 2: Open the dashboard
- Open the .xlsx file using Microsoft Excel.

Step 3: Enable editing
- If prompted, select Enable Editing.

Step 4: Explore the dashboard
- Use the available filters/slicers to explore churn patterns across different customer characteristics.

Step 5: Review the results
- Use the KPIs, charts, and visualizations to understand the key churn patterns identified in the analysis.


