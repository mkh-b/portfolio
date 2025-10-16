# My Portfolio

Welcome to my data portfolio! This is where I document a summary of my projects in the data field.

## Project 1: Salary Distribution Analysis

**Dataset source:** [Kaggle](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data)

**Dataset information:** it contains 6 columns, each column representing a variable: Gender, Age, Education Level, Job Title, Years of Experience, Salary. 
The "Gender" variable presents two classes: "Male" and "Female", the age of the individuals in the dataset varies from 21 until 62, while education is represented in the form of four levels: High School, Bachelor's Degree, Master's Degree and PhD. The dataset also contains a total 183 different job positions, and the number of years each employee has as experience varying from 0 to 34 years. The unit of the variable "Salary" is INR (Indian Rupee).

**Objectives of the analysis:**
- Analyze the salary distribution across different job titles and education levels.
- Determine the average salary for each category.
- Investigate if there is a significant gender pay gap.
- Study the influence of the years of experience on the salary levels.
- Study the impact of the education level and how it affects salary levels.
- Identify the highest paid employees of the dataset, by Age, Years of Experience and Job Title.
- Analyze the correlation between the variables "Age" and "Salary".

**Approach:** performing a simple EDA (Exploratory Data Analysis)

**Tools used:** MySQL for data analysis and Google Looker Studio for data visualization.

**Dashboard:** ([https://lookerstudio.google.com/reporting/abd0dc6d-9b0a-4816-9cb2-237664754725](https://lookerstudio.google.com/s/uxZDc5sghI0))

![salarydata_viz](https://github.com/user-attachments/assets/298e330f-14e1-4e9f-a0cb-9ec4d40d6ffb)

[Check The Process and Results Here](https://github.com/mkh-b/portfolio/blob/main/Project%201%3A%20Process%20%26%20Results)

[Check The MySQL Script Here](https://github.com/mkh-b/portfolio/blob/main/Project%201%3A%20MySQL%20script)

## Project 2: Data-Driven Strategy for Content: Case Study

**Introduction:** 
In this digital age we live in, social media has become a vital part of our lives. Platforms that were once seen as online spaces for socializing are now utilized for matters of business, dating, politics, and daily communication. These platforms remain the top choice for individuals to grow their businesses and brands 
through advertisements and marketing strategies.
Reaching your target audience and bringing new customers on social media isn't always a success, and can be especially challenging for small, medium and newly opened online businesses that don't have an already existing popularity on social platforms, which is where Data Science and Data Analysis come in.
Whether you own a business or you simply aim to grow your platform and its online presence by increasing user engagement and audience reach, you will need a data-driven content strategy to optimize the platform’s engagement and audience growth.
This project is a case study created by Aman Kharwal, posted on statso.io 

**Dataset source:** https://statso.io/data-driven-strategy-for-content-case-study/

**Tools used:** Python for data cleaning and extensive data analysis, Google Sheets for data visualization.

**Objectives of the analysis:**
- What topics should the platform focus on to increase user engagement?
- Which post types should be prioritized to grow followers and interactions?
- What days and times are optimal for posting to achieve maximum reach and impressions?
- What is the best and most effective strategy to grow the platform's online presence and increase user engagement on Instagram?

**Strategy based on Analysis:**
- In order to increase user engagement, the platform should focus on posting more content about "Projects", as it generates the most reach, impressions and likes. "Careeer Growth" is the next best performing topic, although a detailed look at the posts' descriptions shows that "Learning and Education" and "Career Growth" are similar in context and could be used similarly. This finding encourages giving the topic regarding "Learning and Education" more importance, it includes posting challenges, various data science concepts' definitions and learning guides to help with improving skills. These could attract more audience with different data science skills and knowledge levels. In this regard, posting simple and visually appealing roadmaps and easily readable guides is a creative and effective way to reach users who are new to data related content, including reccomendations of online courses they might find helpful (making the learning process of data science concepts accessible, easily understandable and enjoyable for this demographic is a possibility for gaining new faithful followers who engage with the platform regularly in a long term). As for the intermediate, advanced and experienced users who simply want to improve by application rather than theory, the platform could build loyalty and gain them as followers through posting solved and explained projects related to real world events. Observing the bigger picture, "Projects" topic plays a key role in improving engagement in a long term, for many users it's a way to help them gain more skills and build their portfolio in order to land a good job position.
- IG image seems to generate the most impressions and reach, although the ratio between these metrics and the rest of the engagement metrics for images compared to reels and carousels seems to indicate the high number of impressions and reach could be influenced by ADs and promotions, as IG reels performs better than IG carousels and IG images in terms of likes, comments, follows, saves and shares, while carousels are ahead of reels regarding impressions and reach. To link the post type with its content, it is best to post snippets of the projects and the challenges the platform offers in the form of a short reel, this will help with maximizing the platform's reach and attract new eyes on its content. While carousels are more effective when used for the visual guides, roadmaps and short introductory definitions of concepts to drive daily engagement rate growth.
- If the platform's priority is to improve its engagement rate, the analysis shows the best posting times are late at night from 2AM until 5AM when the engagement rate peaks, and also at 9PM and 11PM. While the best days to post and promote the content are Monday, Tuesday and Wednesday.
- If the platform's priority is to generate more impressions and reach more users, the analysis shows the best posting times are around 2AM when the engagement peaks and during the early hours of the day from 6AM until 8AM. While the most optimal days to post and promote the content are Friday and Saturday.

**Summary Table created with Python:**

|    Day    | Best Post Type for Follower Growth | Best Post Type for Interactions | Best Posting Hour|
|-----------|------------------------------------|---------------------------------|------------------|
| Saturday  |              IG image              |              IG reel            |        2:00      |
| Sunday    |              IG reel               |              IG reel            |        8:00      |
| Monday    |              IG carousel           |              IG carousel        |        4:00      |
| Tuesday   |              IG reel               |              IG reel            |        0:00      |
| Wednesday |              IG reel               |              IG reel            |        6:00      |
| Thursday  |              IG reel               |              IG reel            |        7:00      |
| Friday    |              IG reel                |              IG reel            |        20:00     |

[View Full Dashboard and Cleaned Dataset](https://docs.google.com/spreadsheets/d/1Da6SrVzyjV4EB5Y3MXZjkR7qKU-OMsoN/edit?usp=sharing&ouid=107468020496323504064&rtpof=true&sd=true)

## Project 3: Walmart Sales Analysis

**Background:** Walmart Inc. is an American multinational retail corporation that operates a chain of supercenters, discount department stores, and grocery stores in the United States and 23 other countries. The company is headquartered in Bentonville, Arkansas and was founded in 1962 by brothers Sam Walton and James "Bud" Walton in nearby Rogers, Arkansas.

**Overview:** This project focuses on analysing sales data to extract critical business insights and identify opportunities to boost sales and business growth across 98 cities and 100 branches of Walmart in Texas from 01/01/2019 until 31/12/2023.

**Business Questions:**
- Which Category is the Highest Rated, Best Selling and Most Profitable overall and in each Branch?
- Which is the Preferred Payment Method?
- Which City has the Highest Number of Sales?
- What are the Busiest Days and Hours for each Branch?
- Which Period of the Year generates the Most Profit and Revenue?
- What are the Best and Worst Performing Branches?

**Tools used:** Python for Data Cleaning, Data Transformation and extensive Exploratory Data Analysis, Google Looker Studio for Data Visualization.

**Dataset source:** [Kaggle](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)

**Key Results and Insights:**
* 'Fashion Accessories' and 'Home & Lifestyle' are the Best Selling and also the Most Profitable Categories, while the Highest Rated ones are 'Food & Beverages', 'Health & Beauty' and 'Sports & Travel'.
* The most commonly used Payment Methods based on transactions are E-Wallets and Credit Cards.
* Top 5 Cities with the Highest Sales based on Total Quantity are: Weslaco, Waxahachie, Rockwall, Plano, Port Arthur.
* Top 5 Cities with the Highest Sales based on Total Revenue are: Weslaco, Waxahachie, Plano, San Antonio, Port Arthur.
* Top 5 Cities with the Lowest Sales based on Total Quantity are: Burleson, Lewisville, Pearland, Amarillo, Lake Jackson.
* Top 5 Cities with the Lowest Sales based on Total Revenue are: Longview, Pearland, Irving, Lewisville, Lake Jackson.
* On average, the Busiest Hours of the day based on Transactions are from 3pm - 8pm.
* Sundays and Tuesdays tend to derive the Most Customers based on Transactions.
* October, November and December generate the Most Profit and Revenue each year.
* Best Perfoming Branches based on Total Profit: WALM009, WALM030, WALM003, WALM029, WALM046.
* Wost Perfoming Branches based on Total Profit: WALM097, WALM100, WALM092, WALM098, WALM077.

**Strategic Recommendation:**
- 

[View dynamic and interactive dashboard](https://lookerstudio.google.com/embed/reporting/1ea52b0c-e4a1-4828-b592-606fee4873f2/page/w2JbF)
