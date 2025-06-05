🗂️ About the Data
This project analyzes sales transactions from three Amazon branches located in Mandalay, Yangon, and Naypyitaw. The dataset consists of 1000 rows and 17 columns, detailing various aspects of customer transactions such as date, time, product line, payment method, customer type, tax, total sales, and ratings.

🔍 Project Objectives
This project aims to uncover actionable business insights through three key analyses:

1. Product Analysis
Identify top-performing product lines

Recognize underperforming categories

Classify product lines as "Good" or "Bad" based on sales performance

2. Sales Analysis
Understand overall sales trends

Evaluate monthly revenue and costs

Determine the effectiveness of sales strategies by time and day

3. Customer Analysis
Segment customers by gender, type, and location

Analyze purchasing behavior

Identify high-revenue and high-frequency segments

🛠️ Data Processing Steps
1. Data Wrangling
Checked for and removed NULL values during table creation

Cleaned column names and ensured consistent formatting

2. Feature Engineering
timeofday: Categorized sales into Morning, Afternoon, Evening

dayname: Extracted weekday name from transaction date

monthname: Extracted month from transaction date

3. Exploratory Data Analysis (EDA)
Used SQL queries to answer various business questions.

❓ Business Questions Answered
Some of the key questions explored:

Number of unique cities and their branches

Most used payment method

Top-performing product line by sales and revenue

Monthly revenue and peak cost periods

Customer type with the highest revenue and VAT

Distribution of gender across branches

Time and day with highest customer ratings



