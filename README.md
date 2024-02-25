# Business Analysis and SQL Challenge
This repository contains the analysis and solutions to a business problem and SQL challenge provided. Below is a breakdown of the tasks undertaken and the files included in this repository.

## Business Analysis

### Datasets used:

Payments.csv
Clients.csv
Objective:
Identify key trends in payment data to help avoid default-prone customers in the future.

### Analysis Approach:

Data Cleaning and Preprocessing
Exploratory Data Analysis
Dashboard Creation
Dashboard Tool Used:
Tableau

#### Files used/created:

Database/Payments.csv: Original Dataset containing transaction payment details;
Database/Clients.csv: Original Dataset containing client information;
Database/processed.csv: Processed datased joining Clients.csv and Payments.csv in a single source;
Database/processed_withoutDaysElapsedOutliers.csv: processed.csv without outliers for days_elapsed analysis (see Dashboard);
Database/AvgPaidPerClient.csv: payments.csv clustered by client_id to get average payments
Database/TotalPaidPerClient.csv: payments.csv clustered by client_id to get total payments


Analysis.ipynb: Jupyter notebook containing Python code for data analysis.
Dashboard.png: Dashboard visualisations generated from the analysis.


## SQL Challenge
### Objective:
Find the overlap between 2018 payment totals for the biggest clients and their overall payment ranks within each entity.

### Files Created:

SQL_Challenge.ipynb: SQL script containing the solution to the challenge written using pandasql in Python.
challenge_response.csv: CSV file containing the top 20 clients for 2018, their entity type, 2018 total payment amount, and overall payment amount rank within their entity.

# Instructions for Running the Analysis
## Business Analysis:

Ensure Python environment is set up with necessary libraries (pandas, matplotlib, seaborn, etc.).
Open and run Analysis.ipynb in Jupyter Notebook or any compatible environment.
Explore the dashboard visualisations or analysis.ipynb for insights.

## SQL Challenge:

Use the provided python script SQL_Challenge.ipynb
Execute the script to obtain the desired CSV file challenge_response.csv.

# Dashboard link:

url

# Conclusion
The analysis provides valuable insights into payment trends and helps in identifying potential strategies to mitigate default risks. For any questions or further assistance, please contact [Your Name/Email].
