# Data Professionals Survey Portfolio Project
<img width="915" alt="image" src="https://github.com/stefanmills/Data-Professional-Survey-Project-PowerBi/assets/24477861/5c408e15-23ea-4d54-85bb-c0c02c3d5f2e">


## Background

This portfolio project focuses on analyzing a survey taken by data professionals, aiming to gather comprehensive information about their roles, career paths, salary, industry, programming language preferences, job satisfaction, career challenges, job preferences, demographic information, and educational background. The survey respondents were primarily from platforms X and LinkedIn. The data for this project belongs to Alex Goldberg.

The data cleaning and visualization for this project were performed using Power BI.


## Steps

### 1. Download Data

Download the survey data for the task ahead.

### 2. Input Data into Power BI

Import the downloaded data into Power BI.

### 3. Transform Data

Select the inputted data and click "Transform Data" to initiate the data cleaning process.

### 4. Data Cleaning

#### a. Delete Empty Columns

Delete all empty columns, including "Browser," "OS," "City," "Country," and "Referrer."

#### b. Split Columns

Apply the "Split by Delimiter" function to the following columns: "Industry," "Programming Languages," "Country," and "Ethnicity." Group all data specified as "Other" under these columns to just "Others."

#### c. Clean Salary Data

For the "Salary" column, which is originally in a range, apply the split function using the "Digit to Non-Digit" option. This will result in two values in two different columns. Calculate the average of these values in a new column. Delete the two columns used to find the average after completing this step.

### 5. Dashboard Creation

After cleaning the data, create your dashboard using Power BI. Choose visualizations that best suit the project's goals and effectively communicate the insights derived from the survey data.

Feel free to customize the dashboard based on your preferences and the specific aspects of the data you want to highlight.

## Notes

- Ensure that you have Power BI installed to effectively follow the steps mentioned.
- Regularly save your Power BI file to avoid data loss during the process.
- Experiment with various visualizations to enhance the clarity and impact of your dashboard.
