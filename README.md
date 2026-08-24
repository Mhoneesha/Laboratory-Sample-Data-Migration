# Laboratory-Sample-Data-Migration
## About this project

I am using this project to practice working with data and understanding the basic steps involved in a data migration.

I took a sample laboratory dataset and used it to practice checking data, finding mistakes, matching columns between systems, and keeping my work organised.

I am using GitHub to keep the files together and to document the steps I am taking.

## In this project, I am practicing:

Looking at the data,
Checking for missing information,
Looking for duplicate values,
Checking dates,
Checking different names used for the same thing,
Matching old column names with new column names,
Writing down the problems I find,
Making notes about what could be changed before migration,
## Project structure
data/
mapping/
validation/
issues/
transformation/
README.md

data/

This is where I keep the dataset. I started with

mapping/

Here I matched the old column names with the new column names.

For example:

Old column	New column
Sample_No	Sample_ID
Client_Name	Customer_Name
Product	Sample_Type
Received_Date	Date_Received
Test_Type	Analysis_Type
Status	Sample_Status
Analyst	Assigned_Analyst
Result_Date	Date_Completed
validation/

This is where I keep the Excel file where I checked the data.

## I looked for things like:

Empty cells
Duplicate sample numbers
Different status names
Date problems
Missing analyst names
issues/

I keep the problems I find here so I do not forget them.

These issues can then be reviewed before the data is migrated.

transformation/

I use this folder for notes about changes that may be needed in the data before it is used in the new system.

## What I am learning

I am still learning, so I am using this project to get more comfortable with:

Excel
CSV files
Data checking
Data quality
Field mapping
Keeping project information organised with GitHub

I am also trying to understand what happens when data from one system needs to be prepared for use in another system.

## Data

The data used in this project is for practice only.

I did not use any real customer information, sample information, laboratory results, or company data.

This is a self-directed practice project created to help me develop my data and project coordination skills.
