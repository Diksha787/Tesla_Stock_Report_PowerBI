Stock-analysis-of-Tesla-organization
PowerBi Report

By looking at the dataset we have the columns such as:

Date : Data of stock
Open : Opening cost of stock
High : Cost of stock when it was high
Low : Cost of stock when it was low
Close : closing of stock
Volume : Quantity of stock
Adj Close : Adjustment of close
All the above was the defult column i have added few columns such as

year : Extracted from date
Difference_high_low : Difference between the highest cost and lowest cost.
Difference_open_close : Difference between the opening cost and closing cost.
month: From Date
All the formulas to obtain the above columns
1. =(Date.Year([year])) --> year column
2. =([High] - [Low])    --> Difference_high_low
3. =([open] - [close])  --> Difference_open_close
4. =(Date.Month([year])) --> month
Let's start developing the dashboards and the question for the reports are:
image

Question
Based on the year which what was the height quantity of stock owned and what is the lowest quantity of stock owned.
Based on the year what was the cost of opening and closing stocks.
In which year the stock prices was high.
What is the valume of stock per month.
What is the average of opening and closing stock quantity based on year.
What is the cost of stock opening and closing per month.
