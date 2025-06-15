# ElevateLabsAssignments
📊 Customer Personality Analysis – Task 1: Data Cleaning & Preprocessing
Objective:
Prepare and clean the marketing_campaign.csv dataset from the Customer Personality Analysis project for analysis and modeling by handling nulls, duplicates, inconsistent formats, and column naming.

✅ Steps Performed
Step	Description
1.	Renamed all columns to lowercase with underscores for consistency
2.	Converted dt_customer to datetime format (dd-mm-yyyy)
3.	Handled missing values in income using median imputation
4.	Removed duplicate rows
5.	Standardized text fields like education and marital_status
6.	Fixed data types for year_birth, created age and days_as_customer
7.	Exported cleaned data to cleaned_customer_personality.csv

🔍 Tools Used
Python 3

Pandas

📁 Files in This Repo
marketing_campaign.csv – Original dataset (from Kaggle)

clean_customer_personality.py – Cleaning pipeline script

cleaned_customer_personality.csv – Cleaned dataset (output)

README.md – This summary

🚀 Outcome
You now have a clean, enriched dataset with no nulls, duplicates, or format inconsistencies. It’s ready for segmentation, clustering, or campaign analysis.
