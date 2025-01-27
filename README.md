# My Portfolio

Welcome to my data portfolio! This is where I document a summary of my projects in the data field.

## Project 1: Analysing the distribution of salary

**Dataset source:** https://www.kaggle.com/datasets/mohithsairamreddy/salary-data

**Dataset information:** it contains 6 columns, each column representing a variable: Gender, Age, Education Level, Job Title, Years of Experience, Salary. 
The "Gender" variable presents two classes: "Male" and "Female", the age of the individuals in the dataset varies from 21 until 62, while education is represented in the form of four levels: High School, Bachelor's Degree, Master's Degree and PhD. The dataset also contains a total 183 different job positions, and the number of years each employee has as experience varying from 0 to 34 years. The unit of the variable "Salary" is INR (Indian Rupee).

**Objective of the analysis:**
- Determine the average salary for each category.
- Investigate if there is a significant gender pay gap.
- Analyze the salary distribution across different job titles and education levels.
- Study the influence of the years of experience on the salary levels.
- Study the impact of the education level and how it affects salary levels.
- Identify the highest paid employees of the dataset, and which jobs they worked.
- Analyze the correlation between the variables "Age" and "Salary".

**Approach:** performing a simple EDA (Exploratory Data Analysis)

**Tools used:** MySQL, Google Looker Studio.

**Dashboard:** (https://lookerstudio.google.com/reporting/abd0dc6d-9b0a-4816-9cb2-237664754725)
![salarydata_viz_page-0001](https://github.com/user-attachments/assets/c31b70ca-13e0-4584-9b5f-a27151e6bf48)

### The process:
**Data wrangling:**
The initial dataset is raw and presents data with multiple issues, it wasn't possible to start the analysis right away, I used MySQL to clean the data & normalize some variables.

**Analysis and detailed results:**
Once the raw dataset is converted to analysis-ready data, and with the use of MySQL, I took the initiative to analyze the cleaned data and reach the objectives of this project.
- Average salary by gender:

| gender | average_salary |
| ------ | -------------- |
| male   | 121401.2322    |
| female | 107923.4992    |

- Average salary by age groups:

| age_group | average_salary |
| --------- | -------------- |
| 21-29     | 72218.3373     |
| 30-39     | 123996.0643    |
| 40-49     | 166899.1995    |
| 50-62     | 192192.5793    |
