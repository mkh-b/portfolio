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
- Average salary by Gender:

| Gender | Average Salary |
| ------ | -------------- |
| Male   | 121401.2322    |
| Female | 107923.4992    |

- Average salary by Age Group:

| Age Group | Average Salary |
| --------- | -------------- |
| 21-29     | 72218.3373     |
| 30-39     | 123996.0643    |
| 40-49     | 166899.1995    |
| 50-62     | 192192.5793    |

- Average salary by Education Level:

| Education Level | Average Salary |
| -------------------------- | -------------- |
| High School                | 34415.6124     |
| Bachelor's                 | 95124.7740     |
| Master's                   | 130051.1769    |
| PhD                        | 165693.3287    |

- Average salary by Jon Title:

| Job Title                     | Average Salary |
| ------------------------------------- | -------------- |
| CEO                                   | 250000.0000    |
| Chief Technology Officer              | 250000.0000    |
| Chief Data Officer                    | 220000.0000    |
| Director of Data Science              | 204561.4035    |
| Director                              | 200000.0000    |
| VP of Finance                         | 200000.0000    |
| Operations Director                   | 190000.0000    |
| VP of Operations                      | 190000.0000    |
| Director of Human Resources           | 187500.0000    |
| Marketing Director                    | 183984.3750    |
| Director of Engineering               | 180000.0000    |
| Director of Human Capital             | 180000.0000    |
| Director of Sales and Marketing       | 180000.0000    |
| Human Resources Director              | 180000.0000    |
| Director of Finance                   | 175000.0000    |
| Director of Product Management        | 175000.0000    |
| Director of Sales                     | 175000.0000    |
| Director of Operations                | 172727.2727    |
| Software Engineer Manager             | 172654.6170    |
| Director of Business Development      | 170000.0000    |
| Principal Engineer                    | 170000.0000    |
| Senior Project Engineer               | 166225.4873    |
| Data Scientist                        | 166105.9603    |
| Research Scientist                    | 165362.3188    |
| Research Director                     | 163333.3333    |
| Senior Manager                        | 160000.0000    |
| Senior Marketing Director             | 160000.0000    |
| Senior Data Analyst                   | 155000.0000    |
| Senior Data Engineer                  | 155000.0000    |
| Senior UX Designer                    | 155000.0000    |
| Senior Software Engineer              | 151202.3333    |
| Senior Data Scientist                 | 151147.5410    |
| Senior Researcher                     | 150000.0000    |
| Senior Product Designer               | 148000.0000    |
| Financial Manager                     | 143059.7015    |
| Product Manager                       | 142476.0383    |
| Senior Consultant                     | 140000.0000    |
| Senior Research Scientist             | 137959.1837    |
| Director of Marketing                 | 137840.9091    |
| Senior Sales Manager                  | 132500.0000    |
| Senior Human Resources Specialist     | 130000.0000    |
| Senior IT Project Manager             | 130000.0000    |
| Strategy Consultant                   | 130000.0000    |
| Supply Chain Analyst                  | 130000.0000    |
| Senior Project Manager                | 129285.7143    |
| Senior Engineer                       | 127500.0000    |
| Senior Marketing Manager              | 127222.2222    |
| Full Stack Engineer                   | 126814.4623    |
| Senior Product Marketing Manager      | 126594.2029    |
| Data Analyst                          | 125090.9091    |
| Sales Director                        | 123460.3175    |
| Senior Scientist                      | 123333.3333    |
| Content Marketing Manager             | 123150.6849    |
| Director of HR                        | 122028.9855    |
| Senior Product Manager                | 121666.6667    |
| Creative Director                     | 120000.0000    |
| IT Manager                            | 120000.0000    |
| Principal Scientist                   | 120000.0000    |
| Senior Software Architect             | 120000.0000    |
| Project Manager                       | 119090.9091    |
| Senior Software Developer             | 118333.3333    |
| Marketing Manager                     | 117164.7059    |
| Senior Business Analyst               | 116000.0000    |
| Project Engineer                      | 115000.0000    |
| Software Engineer                     | 113243.2432    |
| Senior Financial Analyst              | 112857.1429    |
| Senior Human Resources Manager        | 111960.7843    |
| Operations Analyst                    | 110000.0000    |
| Sales Operations Manager              | 110000.0000    |
| Senior Account Manager                | 110000.0000    |
| Senior Business Development Manager   | 110000.0000    |
| Senior Graphic Designer               | 110000.0000    |
| Senior IT Consultant                  | 110000.0000    |
| Senior IT Support Specialist          | 110000.0000    |
| Software Manager                      | 110000.0000    |
| Human Resources Manager               | 108566.0377    |
| Senior Operations Manager             | 108000.0000    |
| Customer Service Manager              | 105000.0000    |
| Supply Chain Manager                  | 105000.0000    |
| Sales Manager                         | 102946.4286    |
| Back end Developer                    | 102328.2757    |
| Senior Financial Manager              | 100000.0000    |
| Senior Product Development Manager    | 100000.0000    |
| Senior Quality Assurance Analyst      | 100000.0000    |
| Senior Training Specialist            | 100000.0000    |
| Senior Marketing Specialist           | 98750.0000     |
| Senior Operations Coordinator         | 97500.0000     |
| Operations Manager                    | 95938.5965     |
| Financial Advisor                     | 95000.0000     |
| Product Marketing Manager             | 95000.0000     |
| Senior Account Executive              | 95000.0000     |
| Senior Sales Representative           | 95000.0000     |
| Software Project Manager              | 95000.0000     |
| Senior Financial Advisor              | 93333.3333     |
| Senior Marketing Coordinator          | 93333.3333     |
| Digital Marketing Manager             | 93269.2308     |
| Senior Project Coordinator            | 92000.0000     |
| Senior HR Generalist                  | 90904.7619     |
| Business Development Manager          | 90000.0000     |
| Public Relations Manager              | 90000.0000     |
| Senior Marketing Analyst              | 89444.4444     |
| Financial Analyst                     | 87692.3077     |
| Business Intelligence Analyst         | 85000.0000     |
| Senior Accountant                     | 85000.0000     |
| Senior Operations Analyst             | 85000.0000     |
| Front end Developer                   | 84205.5481     |
| Marketing Coordinator                 | 81056.9620     |
| Senior Human Resources Coordinator    | 80000.0000     |
| UX Designer                           | 80000.0000     |
| Business Analyst                      | 77500.0000     |
| Account Manager                       | 75000.0000     |
| HR Generalist                         | 70000.0000     |
| Technical Recruiter                   | 70000.0000     |
| Web Developer                         | 66436.7816     |
| Junior Financial Advisor              | 65000.0000     |
| Marketing Specialist                  | 65000.0000     |
| Office Manager                        | 65000.0000     |
| Recruiter                             | 65000.0000     |
| Training Specialist                   | 65000.0000     |
| UX Researcher                         | 65000.0000     |
| Software Developer                    | 64680.0000     |
| Digital Marketing Specialist          | 63333.3333     |
| Junior Marketing Manager              | 63294.1176     |
| Marketing Analyst                     | 62916.6667     |
| IT Support Specialist                 | 60000.0000     |
| Network Engineer                      | 60000.0000     |
| Social Media Manager                  | 58000.0000     |
| Junior Product Manager                | 56250.0000     |
| Product Designer                      | 56200.0000     |
| Accountant                            | 55000.0000     |
| Junior Operations Manager             | 55000.0000     |
| Junior Marketing Specialist           | 53000.0000     |
| Junior Financial Analyst              | 52857.1429     |
| Event Coordinator                     | 52500.0000     |
| Junior Data Analyst                   | 51360.0000     |
| Junior Operations Analyst             | 51000.0000     |
| Junior Software Engineer              | 50372.5490     |
| Administrative Assistant              | 50000.0000     |
| Digital Content Producer              | 50000.0000     |
| IT Support                            | 50000.0000     |
| Junior Account Manager                | 50000.0000     |
| Junior Business Analyst               | 50000.0000     |
| Junior Research Scientist             | 50000.0000     |
| Graphic Designer                      | 49772.7273     |
| Human Resources Coordinator           | 49081.6327     |
| Junior Marketing Analyst              | 48333.3333     |
| Junior Project Manager                | 47000.0000     |
| Junior Marketing Coordinator          | 46666.6667     |
| Junior Web Developer                  | 45761.9048     |
| Junior Advertising Coordinator        | 45000.0000     |
| Junior Copywriter                     | 45000.0000     |
| Junior Data Scientist                 | 45000.0000     |
| Junior Recruiter                      | 45000.0000     |
| Junior Social Media Manager           | 45000.0000     |
| Junior Social Media Specialist        | 45000.0000     |
| Junior UX Designer                    | 45000.0000     |
| Junior Web Designer                   | 45000.0000     |
| Social Media Specialist               | 45000.0000     |
| Technical Writer                      | 45000.0000     |
| Sales Representative                  | 44078.9474     |
| Sales Executive                       | 43026.3158     |
| Junior Accountant                     | 41666.6667     |
| Junior Business Development Associate | 40714.2857     |
| Copywriter                            | 40000.0000     |
| Customer Success Manager              | 40000.0000     |
| Customer Success Rep                  | 40000.0000     |
| Junior Designer                       | 40000.0000     |
| Junior Developer                      | 40000.0000     |
| Junior Operations Coordinator         | 40000.0000     |
| Technical Support Specialist          | 40000.0000     |
| Junior HR Generalist                  | 38476.1905     |
| Junior HR Coordinator                 | 38093.7500     |
| Junior Sales Representative           | 36951.2195     |
| Sales Associate                       | 35857.1429     |
| Junior Software Developer             | 35810.3448     |
| Data Entry Clerk                      | 35000.0000     |
| Help Desk Analyst                     | 35000.0000     |
| Junior Business Operations Analyst    | 35000.0000     |
| Junior Customer Support Specialist    | 35000.0000     |
| Customer Service Representative       | 34285.7143     |
| Junior Sales Associate                | 28211.2676     |
| Delivery Driver                       | 28000.0000     |
| Receptionist                          | 25000.0000     |
