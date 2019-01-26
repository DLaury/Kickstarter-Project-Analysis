# Kickstarter-Project-Analysis
This project takes information provided by Kickstarter for analysis.
Steps taken:
- Fill each cell based on whether the project was successful, failed, cancelled, or currently live using conditional formatting
- Use formula to create new column called percent funded
- Use conditional formatting to fill this column into three different colors
- Use formula to create new column of average donation
- Use formula to separates Category and Sub-Category into two categories
- Create new sheet and pivot table counting how many campaigns were successful, failed, cancelled, or currently live per category
- Create a stacked column pivot chart that can be filtered by country
- Create new sheet and pivot table counting how many campaigns were successful, failed, cancelled, or currently live per sub-category
- Create stacked column pivot chart that can be filtered by country and parent-category
- Use formula to convert unix timestamps to normal structured date and create two new columns for them
- Create new sheet and pivot table with column of state, rows of date created, and values of state. This can be filtered by parent category and year.
- Create pivot chart line graph based on this data.
- Create a new sheet with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled
- Goals values set to: Less Than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 25000 to 29999, 30000 to 34999, 35000 to 39999, 40000 to 44999, 45000 to 49999, Greater than or equal to 50000
- Using countifs() count successful, failed, cancelled within the ranges
- Calculate total projects column
- Create line chart graphing relationship between goal amount and chances at success, failure, or cancellation
