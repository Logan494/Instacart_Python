# **Customer Purchase Analysis - Instacart Grocery Basket Analysis**

## Project Overview:
Instacart, a successful online grocery store, wanted to gain insights into its sales patterns to create more effective ad campaigns. This analysis focuses on understanding customer purchasing behavior, identifying peak spending times, and simplifying price ranges to better target different customer segments. 

Key questions explored include:
- What are the busiest days of the week and times of the day for orders?
- When do customers spend the most money?
- How can the pricing system be simplified to enhance customer experience?
- How do factors like age, marital status, and the number of children influence purchasing habits?

This analysis aims to inform Instacart's marketing strategies by segmenting customers based on their demographic traits and improving their ad targeting efforts.

## Tools & Skills:
- **Programming Language:** Python
- **Packages:** pandas, NumPy, Matplotlib, Seaborn
- **Data Wrangling & Cleaning:** Integrated and transformed data using Python
- **Data Visualization:** Developed visualizations to highlight key findings
- **Project Environment:** Jupyter Notebooks within Anaconda

## Data Cleaning & Transformation:
Throughout the project, I applied several cleaning and transformation steps to ensure data accuracy and relevance:
- Removed unnecessary columns like 'eval_set' that were not useful for analysis.
- Renamed columns for better clarity.
- Created new variables such as `loyalty_flag` to identify repeat customers.
- Developed custom variables like `region`, `age_group`, and `income_group` to examine how geography, age, and income affect spending.
- Generated additional insights by grouping customers based on family status, number of dependents, and regional traits.

## Visualizations:
Some key visualizations created during this analysis include:
- **Customer Distribution by Age:** Showed that most Instacart users are 60 years or older.
- **Income by Age Scatterplot:** Illustrated that higher income tends to be correlated with older age groups, with most Instacart users earning $100,000 or more annually.
- **Top Departments Ordered:** Bar chart showing that produce and dairy are the most frequently purchased items, while non-essential items present opportunities for increased revenue through targeted marketing.
- **Revenue by Family Status and Region:** Highlighted that married individuals with children in the Southern U.S. generate the highest revenue, helping the marketing team identify key customer profiles to target.

## Recommendations & Findings:
- Instacart should focus ad campaigns on driving orders during mid-week and after 4 PM, when customer engagement tends to be lower.
- Ads should target the early morning hours, as most orders occur later in the day between 9 AM and 4 PM.
- Introducing two clear price categories—"$15 or less" and "Over $15"—can simplify customer decision-making and lead to better targeting.
- Essential products like produce and dairy consistently dominate orders, meaning marketing efforts should shift toward promoting non-essential items for upselling opportunities.

## Learning Experience:
This project provided me with valuable insights into mastering Python for data analysis, particularly through extensive use of libraries like Matplotlib and Seaborn to create meaningful visualizations. I improved my ability to write clean, well-documented code, and the process of data cleaning and transformation deepened my understanding of structuring data for analysis. Continuous practice with Python enhanced my problem-solving abilities and helped me produce higher quality analysis results.
