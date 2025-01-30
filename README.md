# My Portfolio

Welcome to my data portfolio! This is where I document a summary of my projects in the data field.

## Project 1: Analysing the distribution of salary

**Dataset source:** https://www.kaggle.com/datasets/mohithsairamreddy/salary-data

**Dataset information:** it contains 6 columns, each column representing a variable: Gender, Age, Education Level, Job Title, Years of Experience, Salary. 
The "Gender" variable presents two classes: "Male" and "Female", the age of the individuals in the dataset varies from 21 until 62, while education is represented in the form of four levels: High School, Bachelor's Degree, Master's Degree and PhD. The dataset also contains a total 183 different job positions, and the number of years each employee has as experience varying from 0 to 34 years. The unit of the variable "Salary" is INR (Indian Rupee).

**Objective of the analysis:**
- Analyze the salary distribution across different job titles and education levels.
- Determine the average salary for each category.
- Investigate if there is a significant gender pay gap.
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

- Average salary by Job Title:

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

- Average salary by Experience:

| Experience  | Average Salary |
| ----------- | -------------- |
| 0-5 years   | 69129.2459     |
| 6-10 years  | 125036.7617    |
| 11-20 years | 166437.9242    |
| 21-34 years | 187090.9748    |

- Salary distribution by Job Title:

| Job Title                     | Employee Count | Average Salary | Minimum Salary | Maximum Salary |
| ------------------------------------- | -------------- | -------------- | -------------- | -------------- |
| Software Engineer                     | 518            | 113243.2432    | 50000          | 197000         |
| Data Scientist                        | 453            | 166105.9603    | 75000          | 240000         |
| Software Engineer Manager             | 376            | 172654.6170    | 52612          | 210000         |
| Data Analyst                          | 363            | 125090.9091    | 65000          | 195000         |
| Senior Project Engineer               | 316            | 166225.4873    | 51831          | 210000         |
| Product Manager                       | 313            | 142476.0383    | 55000          | 198000         |
| Full Stack Engineer                   | 305            | 126814.4623    | 55000          | 192756         |
| Front end Developer                   | 270            | 84205.5481     | 47898          | 174726         |
| Marketing Manager                     | 255            | 117164.7059    | 55000          | 228000         |
| Back end Developer                    | 243            | 102328.2757    | 51832          | 178284         |
| Senior Software Engineer              | 240            | 151202.3333    | 99747          | 195270         |
| Marketing Coordinator                 | 158            | 81056.9620     | 40000          | 131000         |
| Junior Sales Associate                | 142            | 28211.2676     | 25000          | 35000          |
| Financial Manager                     | 134            | 143059.7015    | 45000          | 250000         |
| Marketing Analyst                     | 132            | 62916.6667     | 40000          | 75000          |
| Software Developer                    | 125            | 64680.0000     | 45000          | 95000          |
| Operations Manager                    | 114            | 95938.5965     | 70000          | 174000         |
| Human Resources Manager               | 106            | 108566.0377    | 75000          | 152000         |
| Director of Marketing                 | 88             | 137840.9091    | 80000          | 200000         |
| Web Developer                         | 87             | 66436.7816     | 35000          | 110000         |
| Product Designer                      | 75             | 56200.0000     | 45000          | 90000          |
| Research Director                     | 75             | 163333.3333    | 150000         | 190000         |
| Content Marketing Manager             | 73             | 123150.6849    | 55000          | 190000         |
| Sales Associate                       | 70             | 35857.1429     | 25000          | 60000          |
| Research Scientist                    | 69             | 165362.3188    | 120000         | 185000         |
| Senior Product Marketing Manager      | 69             | 126594.2029    | 70000          | 200000         |
| Director of HR                        | 69             | 122028.9855    | 80000          | 180000         |
| Marketing Director                    | 64             | 183984.3750    | 160000         | 195000         |
| Sales Director                        | 63             | 123460.3175    | 70000          | 180000         |
| Senior Data Scientist                 | 61             | 151147.5410    | 120000         | 200000         |
| Junior HR Generalist                  | 60             | 38250.0000     | 32000          | 65000          |
| Junior Software Developer             | 58             | 35810.3448     | 35000          | 50000          |
| Director of Data Science              | 57             | 204561.4035    | 170000         | 220000         |
| Receptionist                          | 57             | 25000.0000     | 25000          | 25000          |
| Sales Manager                         | 56             | 102946.4286    | 35000          | 180000         |
| Digital Marketing Manager             | 52             | 93269.2308     | 30000          | 150000         |
| Senior Human Resources Manager        | 51             | 111960.7843    | 70000          | 160000         |
| Junior Marketing Manager              | 51             | 63294.1176     | 50000          | 72000          |
| Junior Software Engineer              | 51             | 50372.5490     | 40000          | 55000          |
| Senior Research Scientist             | 49             | 137959.1837    | 130000         | 160000         |
| Human Resources Coordinator           | 49             | 49081.6327     | 45000          | 60000          |
| Junior Web Developer                  | 42             | 45761.9048     | 40000          | 55000          |
| Senior HR Generalist                  | 42             | 90904.7619     | 55000          | 115000         |
| Junior Sales Representative           | 41             | 36951.2195     | 25000          | 75000          |
| Financial Analyst                     | 39             | 87692.3077     | 55000          | 160000         |
| Sales Executive                       | 38             | 43026.3158     | 35000          | 160000         |
| Sales Representative                  | 38             | 44078.9474     | 30000          | 90000          |
| Junior HR Coordinator                 | 32             | 38093.7500     | 30000          | 60000          |
| Junior Data Analyst                   | 25             | 51360.0000     | 50000          | 60000          |
| Project Manager                       | 22             | 119090.9091    | 95000          | 130000         |
| Graphic Designer                      | 22             | 49772.7273     | 45000          | 60000          |
| Social Media Manager                  | 15             | 58000.0000     | 55000          | 100000         |
| Digital Marketing Specialist          | 15             | 63333.3333     | 60000          | 65000          |
| Director of Operations                | 11             | 172727.2727    | 160000         | 180000         |
| Senior Business Analyst               | 10             | 116000.0000    | 90000          | 150000         |
| Senior Marketing Manager              | 9              | 127222.2222    | 95000          | 170000         |
| Senior Marketing Analyst              | 9              | 89444.4444     | 85000          | 100000         |
| Junior Business Analyst               | 8              | 50000.0000     | 40000          | 60000          |
| Customer Service Representative       | 7              | 34285.7143     | 30000          | 45000          |
| Senior Financial Analyst              | 7              | 112857.1429    | 90000          | 150000         |
| Senior Project Manager                | 7              | 129285.7143    | 120000         | 140000         |
| Junior Financial Analyst              | 7              | 52857.1429     | 40000          | 70000          |
| Junior Business Development Associate | 7              | 40714.2857     | 35000          | 50000          |
| Senior Product Manager                | 6              | 121666.6667    | 95000          | 150000         |
| Junior Marketing Coordinator          | 6              | 46666.6667     | 40000          | 55000          |
| Senior Project Coordinator            | 5              | 92000.0000     | 80000          | 95000          |
| Junior Operations Analyst             | 5              | 51000.0000     | 35000          | 70000          |
| Junior Marketing Specialist           | 5              | 53000.0000     | 40000          | 70000          |
| Junior Project Manager                | 5              | 47000.0000     | 40000          | 60000          |
| Senior Product Designer               | 5              | 148000.0000    | 140000         | 150000         |
| Senior Operations Manager             | 5              | 108000.0000    | 95000          | 120000         |
| Senior Financial Manager              | 5              | 100000.0000    | 90000          | 120000         |
| Delivery Driver                       | 5              | 28000.0000     | 28000          | 28000          |
| Senior Business Development Manager   | 4              | 110000.0000    | 90000          | 120000         |
| Junior Product Manager                | 4              | 56250.0000     | 40000          | 65000          |
| Senior Marketing Specialist           | 4              | 98750.0000     | 85000          | 120000         |
| Senior Data Engineer                  | 4              | 155000.0000    | 150000         | 160000         |
| Senior Operations Coordinator         | 4              | 97500.0000     | 90000          | 120000         |
| Senior Scientist                      | 3              | 123333.3333    | 110000         | 140000         |
| Junior Accountant                     | 3              | 41666.6667     | 35000          | 50000          |
| Junior Marketing Analyst              | 3              | 48333.3333     | 35000          | 70000          |
| Senior Software Developer             | 3              | 118333.3333    | 105000         | 140000         |
| Senior Marketing Coordinator          | 3              | 93333.3333     | 80000          | 110000         |
| Senior UX Designer                    | 3              | 155000.0000    | 145000         | 160000         |
| Senior Data Analyst                   | 3              | 155000.0000    | 150000         | 160000         |
| Senior Financial Advisor              | 3              | 93333.3333     | 80000          | 100000         |
| Junior Operations Manager             | 3              | 55000.0000     | 35000          | 70000          |
| Juniour HR Generalist                 | 3              | 43000.0000     | 43000          | 43000          |
| Senior Manager                        | 2              | 160000.0000    | 150000         | 170000         |
| Senior Engineer                       | 2              | 127500.0000    | 115000         | 140000         |
| Business Analyst                      | 2              | 77500.0000     | 75000          | 80000          |
| Recruiter                             | 2              | 65000.0000     | 60000          | 70000          |
| HR Generalist                         | 2              | 70000.0000     | 60000          | 80000          |
| Administrative Assistant              | 2              | 50000.0000     | 45000          | 55000          |
| Customer Service Manager              | 2              | 105000.0000    | 80000          | 130000         |
| Event Coordinator                     | 2              | 52500.0000     | 45000          | 60000          |
| Junior Account Manager                | 2              | 50000.0000     | 45000          | 55000          |
| Senior Sales Manager                  | 2              | 132500.0000    | 130000         | 135000         |
| Senior Accountant                     | 2              | 85000.0000     | 80000          | 90000          |
| Director of Human Resources           | 2              | 187500.0000    | 185000         | 190000         |
| Senior Sales Representative           | 2              | 95000.0000     | 90000          | 100000         |
| Director of Finance                   | 2              | 175000.0000    | 170000         | 180000         |
| Senior Operations Analyst             | 2              | 85000.0000     | 85000          | 85000          |
| Senior Human Resources Specialist     | 2              | 130000.0000    | 120000         | 140000         |
| Senior IT Consultant                  | 2              | 110000.0000    | 110000         | 110000         |
| Junior Business Operations Analyst    | 2              | 35000.0000     | 35000          | 35000          |
| Director of Engineering               | 2              | 180000.0000    | 180000         | 180000         |
| Director                              | 1              | 200000.0000    | 200000         | 200000         |
| Data Entry Clerk                      | 1              | 35000.0000     | 35000          | 35000          |
| VP of Operations                      | 1              | 190000.0000    | 190000         | 190000         |
| IT Support                            | 1              | 50000.0000     | 50000          | 50000          |
| Social Media Specialist               | 1              | 45000.0000     | 45000          | 45000          |
| Software Manager                      | 1              | 110000.0000    | 110000         | 110000         |
| Junior Developer                      | 1              | 40000.0000     | 40000          | 40000          |
| Senior Consultant                     | 1              | 140000.0000    | 140000         | 140000         |
| CEO                                   | 1              | 250000.0000    | 250000         | 250000         |
| Accountant                            | 1              | 55000.0000     | 55000          | 55000          |
| Marketing Specialist                  | 1              | 65000.0000     | 65000          | 65000          |
| Technical Writer                      | 1              | 45000.0000     | 45000          | 45000          |
| Project Engineer                      | 1              | 115000.0000    | 115000         | 115000         |
| Customer Success Rep                  | 1              | 40000.0000     | 40000          | 40000          |
| UX Designer                           | 1              | 80000.0000     | 80000          | 80000          |
| Operations Director                   | 1              | 190000.0000    | 190000         | 190000         |
| Network Engineer                      | 1              | 60000.0000     | 60000          | 60000          |
| Strategy Consultant                   | 1              | 130000.0000    | 130000         | 130000         |
| Copywriter                            | 1              | 40000.0000     | 40000          | 40000          |
| Account Manager                       | 1              | 75000.0000     | 75000          | 75000          |
| Help Desk Analyst                     | 1              | 35000.0000     | 35000          | 35000          |
| Business Intelligence Analyst         | 1              | 85000.0000     | 85000          | 85000          |
| VP of Finance                         | 1              | 200000.0000    | 200000         | 200000         |
| UX Researcher                         | 1              | 65000.0000     | 65000          | 65000          |
| IT Manager                            | 1              | 120000.0000    | 120000         | 120000         |
| Business Development Manager          | 1              | 90000.0000     | 90000          | 90000          |
| Technical Support Specialist          | 1              | 40000.0000     | 40000          | 40000          |
| Creative Director                     | 1              | 120000.0000    | 120000         | 120000         |
| Human Resources Director              | 1              | 180000.0000    | 180000         | 180000         |
| Technical Recruiter                   | 1              | 70000.0000     | 70000          | 70000          |
| Chief Technology Officer              | 1              | 250000.0000    | 250000         | 250000         |
| Junior Designer                       | 1              | 40000.0000     | 40000          | 40000          |
| Financial Advisor                     | 1              | 95000.0000     | 95000          | 95000          |
| Principal Scientist                   | 1              | 120000.0000    | 120000         | 120000         |
| Supply Chain Manager                  | 1              | 105000.0000    | 105000         | 105000         |
| Training Specialist                   | 1              | 65000.0000     | 65000          | 65000          |
| Public Relations Manager              | 1              | 90000.0000     | 90000          | 90000          |
| Operations Analyst                    | 1              | 110000.0000    | 110000         | 110000         |
| Product Marketing Manager             | 1              | 95000.0000     | 95000          | 95000          |
| Chief Data Officer                    | 1              | 220000.0000    | 220000         | 220000         |
| Digital Content Producer              | 1              | 50000.0000     | 50000          | 50000          |
| IT Support Specialist                 | 1              | 60000.0000     | 60000          | 60000          |
| Customer Success Manager              | 1              | 40000.0000     | 40000          | 40000          |
| Senior Graphic Designer               | 1              | 110000.0000    | 110000         | 110000         |
| Software Project Manager              | 1              | 95000.0000     | 95000          | 95000          |
| Supply Chain Analyst                  | 1              | 130000.0000    | 130000         | 130000         |
| Office Manager                        | 1              | 65000.0000     | 65000          | 65000          |
| Principal Engineer                    | 1              | 170000.0000    | 170000         | 170000         |
| Sales Operations Manager              | 1              | 110000.0000    | 110000         | 110000         |
| Junior Web Designer                   | 1              | 45000.0000     | 45000          | 45000          |
| Senior Training Specialist            | 1              | 100000.0000    | 100000         | 100000         |
| Director of Sales                     | 1              | 175000.0000    | 175000         | 175000         |
| Junior Recruiter                      | 1              | 45000.0000     | 45000          | 45000          |
| Junior Customer Support Specialist    | 1              | 35000.0000     | 35000          | 35000          |
| Senior IT Support Specialist          | 1              | 110000.0000    | 110000         | 110000         |
| Director of Product Management        | 1              | 175000.0000    | 175000         | 175000         |
| Junior Copywriter                     | 1              | 45000.0000     | 45000          | 45000          |
| Senior Account Manager                | 1              | 110000.0000    | 110000         | 110000         |
| Senior Researcher                     | 1              | 150000.0000    | 150000         | 150000         |
| Junior Data Scientist                 | 1              | 45000.0000     | 45000          | 45000          |
| Senior Human Resources Coordinator    | 1              | 80000.0000     | 80000          | 80000          |
| Senior IT Project Manager             | 1              | 130000.0000    | 130000         | 130000         |
| Senior Quality Assurance Analyst      | 1              | 100000.0000    | 100000         | 100000         |
| Director of Sales and Marketing       | 1              | 180000.0000    | 180000         | 180000         |
| Senior Account Executive              | 1              | 95000.0000     | 95000          | 95000          |
| Director of Business Development      | 1              | 170000.0000    | 170000         | 170000         |
| Junior Social Media Manager           | 1              | 45000.0000     | 45000          | 45000          |
| Director of Human Capital             | 1              | 180000.0000    | 180000         | 180000         |
| Junior Advertising Coordinator        | 1              | 45000.0000     | 45000          | 45000          |
| Junior UX Designer                    | 1              | 45000.0000     | 45000          | 45000          |
| Senior Marketing Director             | 1              | 160000.0000    | 160000         | 160000         |
| Junior Social Media Specialist        | 1              | 45000.0000     | 45000          | 45000          |
| Senior Product Development Manager    | 1              | 100000.0000    | 100000         | 100000         |
| Senior Software Architect             | 1              | 120000.0000    | 120000         | 120000         |
| Junior Research Scientist             | 1              | 50000.0000     | 50000          | 50000          |
| Junior Operations Coordinator         | 1              | 40000.0000     | 40000          | 40000          |
| Junior Financial Advisor              | 1              | 65000.0000     | 65000          | 65000          |

- Salary distribution by Gender:

| gender | employee_count | average_salary | minimum_salary | maximum_salary |
| ------ | -------------- | -------------- | -------------- | -------------- |
| Male   | 3674           | 121401.2322    | 25000          | 250000         |
| Female | 3013           | 107923.4992    | 25000          | 220000         |

- Salary distribution by Experience:

| Experience  | Employee Count | Average Salary | Minimum Salary | Maximum Salary |
| ----------- | -------------- | -------------- | -------------- | -------------- |
| 0-5 years   | 2802           | 69129.2459     | 25000          | 182000         |
| 6-10 years  | 1788           | 125036.7617    | 45000          | 195000         |
| 11-20 years | 1859           | 166437.9242    | 60000          | 220000         |
| 21-34 years | 238            | 187090.9748    | 121450         | 250000         |

- Salary distribution by Age Group:

| Age Group | Employee Count | Average Salary | Minimum Salary | Maximum Salary |
| ---------- | -------------- | -------------- | -------------- | -------------- |
| 21-29      | 2440           | 72218.3373     | 25000          | 182000         |
| 30-39      | 2813           | 123996.0643    | 25000          | 210000         |
| 40-49      | 1163           | 166899.1995    | 60000          | 250000         |
| 50-62      | 271            | 192192.5793    | 121450         | 250000         |

- Salary distribution by Education Level:

| Education Level | Employee Count | Average Salary | Minimum Salary | Maximum Salary |
| -------------------------- | -------------- | -------------- | -------------- | -------------- |
| High School                | 436            | 34415.6124     | 25000          | 165919         |
| Bachelor's                 | 3022           | 95124.7740     | 30000          | 250000         |
| Master's                   | 1860           | 130051.1769    | 32000          | 228000         |
| PhD                        | 1369           | 165693.3287    | 30000          | 250000         |

- Impact of Education Level on Salary and Job Title:

| Education Level | Job Title                     | Employee Count | Average Salary |
| -------------------------- | ------------------------------------- | -------------- | -------------- |
| Bachelor's                 | Software Engineer                     | 478            | 115585.7741    |
| Bachelor's                 | Data Analyst                          | 287            | 129783.9721    |
| Bachelor's                 | Front end Developer                   | 209            | 81234.5550     |
| Bachelor's                 | Product Manager                       | 156            | 117051.2821    |
| Bachelor's                 | Back end Developer                    | 145            | 98743.8483     |
| Bachelor's                 | Marketing Analyst                     | 132            | 62916.6667     |
| Bachelor's                 | Software Developer                    | 118            | 63728.8136     |
| Bachelor's                 | Operations Manager                    | 114            | 95938.5965     |
| Bachelor's                 | Marketing Coordinator                 | 112            | 71205.3571     |
| Bachelor's                 | Full Stack Engineer                   | 104            | 122097.2788    |
| Bachelor's                 | Financial Manager                     | 82             | 162682.9268    |
| Bachelor's                 | Product Designer                      | 74             | 55743.2432     |
| Bachelor's                 | Junior Software Developer             | 58             | 35810.3448     |
| Bachelor's                 | Senior Project Engineer               | 56             | 140110.1429    |
| Bachelor's                 | Junior Marketing Manager              | 51             | 63294.1176     |
| Bachelor's                 | Junior Software Engineer              | 51             | 50372.5490     |
| Bachelor's                 | Human Resources Manager               | 50             | 86160.0000     |
| Bachelor's                 | Web Developer                         | 50             | 61900.0000     |
| Bachelor's                 | Sales Director                        | 43             | 108558.1395    |
| Bachelor's                 | Marketing Manager                     | 42             | 95595.2381     |
| Bachelor's                 | Junior Web Developer                  | 37             | 45540.5405     |
| Bachelor's                 | Sales Manager                         | 34             | 125441.1765    |
| Bachelor's                 | Content Marketing Manager             | 27             | 113148.1481    |
| Bachelor's                 | Senior Software Engineer              | 27             | 127651.1111    |
| Bachelor's                 | Software Engineer Manager             | 26             | 137666.2308    |
| Bachelor's                 | Junior Data Analyst                   | 25             | 51360.0000     |
| Bachelor's                 | Sales Representative                  | 22             | 41590.9091     |
| Bachelor's                 | Digital Marketing Manager             | 22             | 91136.3636     |
| Bachelor's                 | Graphic Designer                      | 22             | 49772.7273     |
| Bachelor's                 | Project Manager                       | 21             | 118571.4286    |
| Bachelor's                 | Senior Product Marketing Manager      | 20             | 85750.0000     |
| Bachelor's                 | Financial Analyst                     | 19             | 77631.5789     |
| Bachelor's                 | Junior HR Generalist                  | 19             | 47526.3158     |
| Bachelor's                 | Junior Sales Representative           | 16             | 49062.5000     |
| Bachelor's                 | Digital Marketing Specialist          | 15             | 63333.3333     |
| Bachelor's                 | Social Media Manager                  | 15             | 58000.0000     |
| Bachelor's                 | Director of Marketing                 | 15             | 80000.0000     |
| Bachelor's                 | Junior HR Coordinator                 | 14             | 43928.5714     |
| Bachelor's                 | Sales Executive                       | 12             | 53750.0000     |
| Bachelor's                 | Junior Business Analyst               | 8              | 50000.0000     |
| Bachelor's                 | Data Scientist                        | 8              | 179375.0000    |
| Bachelor's                 | Junior Business Development Associate | 7              | 40714.2857     |
| Bachelor's                 | Human Resources Coordinator           | 7              | 50571.4286     |
| Bachelor's                 | Junior Financial Analyst              | 7              | 52857.1429     |
| Bachelor's                 | Senior Marketing Analyst              | 7              | 87142.8571     |
| Bachelor's                 | Junior Marketing Coordinator          | 6              | 46666.6667     |
| Bachelor's                 | Sales Associate                       | 5              | 46000.0000     |
| Bachelor's                 | Senior Business Analyst               | 5              | 103000.0000    |
| Bachelor's                 | Junior Project Manager                | 5              | 47000.0000     |
| Bachelor's                 | Senior Financial Manager              | 5              | 100000.0000    |
| Bachelor's                 | Junior Operations Analyst             | 5              | 51000.0000     |
| Bachelor's                 | Senior Product Manager                | 5              | 122000.0000    |
| Bachelor's                 | Senior Project Manager                | 5              | 126000.0000    |
| Bachelor's                 | Senior Operations Coordinator         | 4              | 97500.0000     |
| Bachelor's                 | Senior Financial Analyst              | 4              | 112500.0000    |
| Bachelor's                 | Junior Marketing Specialist           | 4              | 56250.0000     |
| Bachelor's                 | Senior Operations Manager             | 4              | 106250.0000    |
| Bachelor's                 | Senior Marketing Specialist           | 4              | 98750.0000     |
| Bachelor's                 | Senior Project Coordinator            | 4              | 95000.0000     |
| Bachelor's                 | Senior Marketing Manager              | 4              | 106250.0000    |
| Bachelor's                 | Junior Product Manager                | 4              | 56250.0000     |
| Bachelor's                 | Senior Business Development Manager   | 3              | 106666.6667    |
| Bachelor's                 | Junior Marketing Analyst              | 3              | 48333.3333     |
| Bachelor's                 | Junior Operations Manager             | 3              | 55000.0000     |
| Bachelor's                 | Junior Accountant                     | 3              | 41666.6667     |
| Bachelor's                 | Senior Marketing Coordinator          | 3              | 93333.3333     |
| Bachelor's                 | HR Generalist                         | 2              | 70000.0000     |
| Bachelor's                 | Event Coordinator                     | 2              | 52500.0000     |
| Bachelor's                 | Senior Sales Representative           | 2              | 95000.0000     |
| Bachelor's                 | Junior Business Operations Analyst    | 2              | 35000.0000     |
| Bachelor's                 | Customer Service Manager              | 2              | 105000.0000    |
| Bachelor's                 | Administrative Assistant              | 2              | 50000.0000     |
| Bachelor's                 | Customer Service Representative       | 2              | 42500.0000     |
| Bachelor's                 | Recruiter                             | 2              | 65000.0000     |
| Bachelor's                 | Senior Accountant                     | 2              | 85000.0000     |
| Bachelor's                 | Junior Account Manager                | 2              | 50000.0000     |
| Bachelor's                 | Senior HR Generalist                  | 2              | 95000.0000     |
| Bachelor's                 | Senior Operations Analyst             | 2              | 85000.0000     |
| Bachelor's                 | Senior Sales Manager                  | 2              | 132500.0000    |
| Bachelor's                 | Software Project Manager              | 1              | 95000.0000     |
| Bachelor's                 | Supply Chain Analyst                  | 1              | 130000.0000    |
| Bachelor's                 | Office Manager                        | 1              | 65000.0000     |
| Bachelor's                 | Sales Operations Manager              | 1              | 110000.0000    |
| Bachelor's                 | Junior Web Designer                   | 1              | 45000.0000     |
| Bachelor's                 | Junior Recruiter                      | 1              | 45000.0000     |
| Bachelor's                 | Junior Customer Support Specialist    | 1              | 35000.0000     |
| Bachelor's                 | Senior IT Support Specialist          | 1              | 110000.0000    |
| Bachelor's                 | Technical Support Specialist          | 1              | 40000.0000     |
| Bachelor's                 | Data Entry Clerk                      | 1              | 35000.0000     |
| Bachelor's                 | Junior Copywriter                     | 1              | 45000.0000     |
| Bachelor's                 | Senior Account Manager                | 1              | 110000.0000    |
| Bachelor's                 | IT Support                            | 1              | 50000.0000     |
| Bachelor's                 | Senior Human Resources Coordinator    | 1              | 80000.0000     |
| Bachelor's                 | Social Media Specialist               | 1              | 45000.0000     |
| Bachelor's                 | Senior IT Project Manager             | 1              | 130000.0000    |
| Bachelor's                 | Junior Developer                      | 1              | 40000.0000     |
| Bachelor's                 | Senior Quality Assurance Analyst      | 1              | 100000.0000    |
| Bachelor's                 | Senior Account Executive              | 1              | 95000.0000     |
| Bachelor's                 | CEO                                   | 1              | 250000.0000    |
| Bachelor's                 | Accountant                            | 1              | 55000.0000     |
| Bachelor's                 | Marketing Specialist                  | 1              | 65000.0000     |
| Bachelor's                 | Technical Writer                      | 1              | 45000.0000     |
| Bachelor's                 | Junior Social Media Manager           | 1              | 45000.0000     |
| Bachelor's                 | Customer Success Rep                  | 1              | 40000.0000     |
| Bachelor's                 | Junior Advertising Coordinator        | 1              | 45000.0000     |
| Bachelor's                 | Junior Social Media Specialist        | 1              | 45000.0000     |
| Bachelor's                 | Network Engineer                      | 1              | 60000.0000     |
| Bachelor's                 | Senior Product Development Manager    | 1              | 100000.0000    |
| Bachelor's                 | Copywriter                            | 1              | 40000.0000     |
| Bachelor's                 | Account Manager                       | 1              | 75000.0000     |
| Bachelor's                 | Junior Operations Coordinator         | 1              | 40000.0000     |
| Bachelor's                 | Help Desk Analyst                     | 1              | 35000.0000     |
| Bachelor's                 | Junior Financial Advisor              | 1              | 65000.0000     |
| Bachelor's                 | IT Manager                            | 1              | 120000.0000    |
| Bachelor's                 | Technical Recruiter                   | 1              | 70000.0000     |
| Bachelor's                 | Junior Designer                       | 1              | 40000.0000     |
| Bachelor's                 | Supply Chain Manager                  | 1              | 105000.0000    |
| Bachelor's                 | Business Analyst                      | 1              | 75000.0000     |
| Bachelor's                 | Training Specialist                   | 1              | 65000.0000     |
| Bachelor's                 | Operations Analyst                    | 1              | 110000.0000    |
| Bachelor's                 | Digital Content Producer              | 1              | 50000.0000     |
| Bachelor's                 | IT Support Specialist                 | 1              | 60000.0000     |
| Bachelor's                 | Customer Success Manager              | 1              | 40000.0000     |
| High School                | Junior Sales Associate                | 142            | 28211.2676     |
| High School                | Sales Associate                       | 65             | 35076.9231     |
| High School                | Receptionist                          | 57             | 25000.0000     |
| High School                | Junior HR Generalist                  | 29             | 34068.9655     |
| High School                | Sales Executive                       | 26             | 38076.9231     |
| High School                | Junior Sales Representative           | 25             | 29200.0000     |
| High School                | Junior HR Coordinator                 | 18             | 33555.5556     |
| High School                | Sales Manager                         | 15             | 40000.0000     |
| High School                | Back end Developer                    | 13             | 69669.3077     |
| High School                | Sales Representative                  | 7              | 41428.5714     |
| High School                | Senior Project Engineer               | 6              | 103628.3333    |
| High School                | Digital Marketing Manager             | 6              | 40000.0000     |
| High School                | Customer Service Representative       | 5              | 31000.0000     |
| High School                | Financial Manager                     | 5              | 51000.0000     |
| High School                | Delivery Driver                       | 5              | 28000.0000     |
| High School                | Junior Web Developer                  | 3              | 47000.0000     |
| High School                | Juniour HR Generalist                 | 3              | 43000.0000     |
| High School                | Web Developer                         | 3              | 41666.6667     |
| High School                | Senior Software Engineer              | 2              | 165919.0000    |
| High School                | Front end Developer                   | 1              | 47898.0000     |
| Master's                   | Full Stack Engineer                   | 193            | 128617.6995    |
| Master's                   | Marketing Manager                     | 182            | 129269.2308    |
| Master's                   | Senior Software Engineer              | 179            | 151594.9944    |
| Master's                   | Product Manager                       | 152            | 166842.1053    |
| Master's                   | Data Scientist                        | 115            | 163782.6087    |
| Master's                   | Back end Developer                    | 85             | 113437.7882    |
| Master's                   | Software Engineer Manager             | 80             | 161983.1000    |
| Master's                   | Data Analyst                          | 76             | 107368.4211    |
| Master's                   | Senior Project Engineer               | 74             | 136122.0405    |
| Master's                   | Marketing Director                    | 64             | 183984.3750    |
| Master's                   | Front end Developer                   | 60             | 95159.6333     |
| Master's                   | Human Resources Manager               | 56             | 128571.4286    |
| Master's                   | Marketing Coordinator                 | 45             | 104711.1111    |
| Master's                   | Content Marketing Manager             | 44             | 127840.9091    |
| Master's                   | Financial Manager                     | 44             | 120681.8182    |
| Master's                   | Human Resources Coordinator           | 42             | 48833.3333     |
| Master's                   | Senior HR Generalist                  | 40             | 90700.0000     |
| Master's                   | Software Engineer                     | 40             | 85250.0000     |
| Master's                   | Web Developer                         | 34             | 75294.1176     |
| Master's                   | Director of Marketing                 | 30             | 152166.6667    |
| Master's                   | Director of HR                        | 26             | 112692.3077    |
| Master's                   | Senior Human Resources Manager        | 26             | 95384.6154     |
| Master's                   | Senior Data Scientist                 | 24             | 122500.0000    |
| Master's                   | Digital Marketing Manager             | 23             | 111956.5217    |
| Master's                   | Financial Analyst                     | 20             | 97250.0000     |
| Master's                   | Junior HR Generalist                  | 12             | 33666.6667     |
| Master's                   | Director of Operations                | 8              | 170000.0000    |
| Master's                   | Software Developer                    | 7              | 80714.2857     |
| Master's                   | Senior Product Marketing Manager      | 7              | 177142.8571    |
| Master's                   | Sales Manager                         | 7              | 128571.4286    |
| Master's                   | Senior Financial Advisor              | 3              | 93333.3333     |
| Master's                   | Senior Financial Analyst              | 3              | 113333.3333    |
| Master's                   | Senior Software Developer             | 3              | 118333.3333    |
| Master's                   | Senior Marketing Manager              | 3              | 146666.6667    |
| Master's                   | Sales Representative                  | 3              | 46666.6667     |
| Master's                   | Senior IT Consultant                  | 2              | 110000.0000    |
| Master's                   | Senior Human Resources Specialist     | 2              | 130000.0000    |
| Master's                   | Junior Web Developer                  | 2              | 48000.0000     |
| Master's                   | Senior Project Manager                | 2              | 137500.0000    |
| Master's                   | Senior Business Analyst               | 2              | 97500.0000     |
| Master's                   | Director of Finance                   | 2              | 175000.0000    |
| Master's                   | Senior Marketing Analyst              | 2              | 97500.0000     |
| Master's                   | Creative Director                     | 1              | 120000.0000    |
| Master's                   | Junior Research Scientist             | 1              | 50000.0000     |
| Master's                   | Senior Project Coordinator            | 1              | 80000.0000     |
| Master's                   | Product Marketing Manager             | 1              | 95000.0000     |
| Master's                   | Junior Data Scientist                 | 1              | 45000.0000     |
| Master's                   | Public Relations Manager              | 1              | 90000.0000     |
| Master's                   | Junior Marketing Specialist           | 1              | 40000.0000     |
| Master's                   | Director of Engineering               | 1              | 180000.0000    |
| Master's                   | Operations Director                   | 1              | 190000.0000    |
| Master's                   | Financial Advisor                     | 1              | 95000.0000     |
| Master's                   | Human Resources Director              | 1              | 180000.0000    |
| Master's                   | Director                              | 1              | 200000.0000    |
| Master's                   | Project Manager                       | 1              | 130000.0000    |
| Master's                   | Business Analyst                      | 1              | 80000.0000     |
| Master's                   | VP of Operations                      | 1              | 190000.0000    |
| Master's                   | Software Manager                      | 1              | 110000.0000    |
| Master's                   | Product Designer                      | 1              | 90000.0000     |
| Master's                   | Project Engineer                      | 1              | 115000.0000    |
| Master's                   | Business Development Manager          | 1              | 90000.0000     |
| Master's                   | UX Designer                           | 1              | 80000.0000     |
| Master's                   | Strategy Consultant                   | 1              | 130000.0000    |
| Master's                   | Business Intelligence Analyst         | 1              | 85000.0000     |
| Master's                   | Senior Operations Manager             | 1              | 115000.0000    |
| Master's                   | Director of Product Management        | 1              | 175000.0000    |
| Master's                   | Director of Business Development      | 1              | 170000.0000    |
| Master's                   | Senior Training Specialist            | 1              | 100000.0000    |
| Master's                   | UX Researcher                         | 1              | 65000.0000     |
| Master's                   | Director of Human Capital             | 1              | 180000.0000    |
| Master's                   | Junior UX Designer                    | 1              | 45000.0000     |
| Master's                   | Senior Product Manager                | 1              | 120000.0000    |
| Master's                   | Senior Business Development Manager   | 1              | 120000.0000    |
| Master's                   | Director of Sales                     | 1              | 175000.0000    |
| Master's                   | Senior Graphic Designer               | 1              | 110000.0000    |
| Master's                   | Senior Software Architect             | 1              | 120000.0000    |
| Master's                   | Director of Human Resources           | 1              | 190000.0000    |
| Master's                   | VP of Finance                         | 1              | 200000.0000    |
| PhD                        | Data Scientist                        | 330            | 166593.9394    |
| PhD                        | Software Engineer Manager             | 270            | 179185.8000    |
| PhD                        | Senior Project Engineer               | 180            | 188812.6944    |
| PhD                        | Research Director                     | 75             | 163333.3333    |
| PhD                        | Research Scientist                    | 69             | 165362.3188    |
| PhD                        | Director of Data Science              | 57             | 204561.4035    |
| PhD                        | Senior Research Scientist             | 49             | 137959.1837    |
| PhD                        | Director of Marketing                 | 43             | 148023.2558    |
| PhD                        | Director of HR                        | 43             | 127674.4186    |
| PhD                        | Senior Product Marketing Manager      | 42             | 137619.0476    |
| PhD                        | Senior Data Scientist                 | 37             | 169729.7297    |
| PhD                        | Senior Software Engineer              | 32             | 167957.4375    |
| PhD                        | Marketing Manager                     | 31             | 75322.5806     |
| PhD                        | Senior Human Resources Manager        | 25             | 129200.0000    |
| PhD                        | Sales Director                        | 20             | 155500.0000    |
| PhD                        | Full Stack Engineer                   | 8              | 144634.7500    |
| PhD                        | Sales Representative                  | 6              | 55000.0000     |
| PhD                        | Senior Product Designer               | 5              | 148000.0000    |
| PhD                        | Product Manager                       | 5              | 195000.0000    |
| PhD                        | Senior Data Engineer                  | 4              | 155000.0000    |
| PhD                        | Director of Operations                | 3              | 180000.0000    |
| PhD                        | Senior Data Analyst                   | 3              | 155000.0000    |
| PhD                        | Senior Scientist                      | 3              | 123333.3333    |
| PhD                        | Financial Manager                     | 3              | 88333.3333     |
| PhD                        | Senior UX Designer                    | 3              | 155000.0000    |
| PhD                        | Senior Business Analyst               | 3              | 150000.0000    |
| PhD                        | Content Marketing Manager             | 2              | 155000.0000    |
| PhD                        | Senior Manager                        | 2              | 160000.0000    |
| PhD                        | Senior Engineer                       | 2              | 127500.0000    |
| PhD                        | Senior Marketing Manager              | 2              | 140000.0000    |
| PhD                        | Principal Engineer                    | 1              | 170000.0000    |
| PhD                        | Senior Consultant                     | 1              | 140000.0000    |
| phD                        | Marketing Coordinator                 | 1              | 120000.0000    |
| PhD                        | Senior Researcher                     | 1              | 150000.0000    |
| PhD                        | Director of Engineering               | 1              | 180000.0000    |
| PhD                        | Senior Marketing Director             | 1              | 160000.0000    |
| PhD                        | Principal Scientist                   | 1              | 120000.0000    |
| PhD                        | Director of Sales and Marketing       | 1              | 180000.0000    |
| PhD                        | Chief Data Officer                    | 1              | 220000.0000    |
| PhD                        | Chief Technology Officer              | 1              | 250000.0000    |
| PhD                        | Director of Human Resources           | 1              | 185000.0000    |
| PhD                        | Digital Marketing Manager             | 1              | 30000.0000     |

- Highest-paid employees by Age:

| Age | Salary    |
| --- | --------- |
| 52  | 250000    |
| 50  | 250000    |
| 45  | 250000    |
| 51  | 240000    |
| 49  | 228000    |
| 50  | 225000    |
| 49  | 220000    |
| 46  | 220000    |
| 44  | 220000    |
| 48  | 219000    |

- Highest-paid employees by Job Title:

| Job Title                | Salary |
| ------------------------ | ------ |
| Chief Technology Officer | 250000 |
| Financial Manager        | 250000 |
| CEO                      | 250000 |
| Data Scientist           | 240000 |
| Marketing Manager        | 228000 |
| Data Scientist           | 225000 |
| Chief Data Officer       | 220000 |
| Director of Data Science | 220000 |
| Data Scientist           | 220000 |
| Data Scientist           | 219000 |

- Highest-paid employees by Years of Experience:

| Years of Experience | Salary |
| ------------------- | ------ |
| 24                  | 250000 |
| 21                  | 250000 |
| 25                  | 250000 |
| 24                  | 240000 |
| 23                  | 228000 |
| 23                  | 225000 |
| 22                  | 220000 |
| 16                  | 220000 |
| 20                  | 220000 |
| 22                  | 219000 |
