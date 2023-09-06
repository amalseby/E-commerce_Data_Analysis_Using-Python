# E-commerce-Data-Analysis for Sales Strategy

In their annual sales review meeting, Kmart, one of the largest online retailers in the US, must decide on their sales strategy for 2020 based on insights from the 2019 sales data.

This project focuses on generating key insights regarding Kmart's sales for each month of 2019. 
The data will be used to assist Kmart's sales team in fine-tuning sales strategies as the year progresses.
# Business Problem Statements
Observations on the following are made:

1)What was the best month for sales? <br>
2)Which city had the highest number of sales?<br>
3)Best time to display advertising to maximize sales?<br>
4)Best-selling product & Why?<br>
5)What products are most often sold together?<br>

# Dataset
* Data belongs to Kmart: A leading online retailer in the US <br>
* Time Period :  January 2019  -  December 2019 <br>
* Unique Products:  19 <br>
* Total Orders :  178,437 <br>
* Cities :  9<br>
* KPI’s : Total Sales, Total Products Sold <br>

# Data Analysis Using Python
1)Loaded data for each month and created a data frame using Pandas.<br>
2)For 2019 sales, an aggregated dataset was created by concatenating multiple datasets together.<br>
3)Data handling for null values and junk data.<br>
4)Preprocessed data to make a filtered dataset.<br>
5)Business problem analysis and their solutions. (visualizations using matplotlib and seaborn library)<br>

# What was the best month for sales?
*Create a new dataset with all records grouped by month<br>
*Plot the graph using matplotlib<br>
<img width="403" alt="Screen Shot 2023-09-07 at 1 03 26 am" src="https://github.com/amalseby/python1/assets/60167060/bf61b536-75a8-4398-b331-7df10e7089b2"><img width="648" alt="Screen Shot 2023-09-07 at 1 03 50 am" src="https://github.com/amalseby/python1/assets/60167060/bf16a206-dc80-4c08-8139-03d9d3d4f3ad">

# Which city had the highest number of sales?
*Extract the “Purchase Address” column containing the city information into a separate dataframe.<br>
*Group this dataframe by City and each group will have a sum of all the sales in that city.<br>
*Visualize the graph using matplotlib<br>
<img width="586" alt="Screen Shot 2023-09-07 at 1 05 56 am" src="https://github.com/amalseby/python1/assets/60167060/f56ea894-eda2-488f-8eae-b73091eef65a">
# Best time to display advertising to maximize sales?
*Extract the Hours from the Order Date.<br>
*Group the data by Hours and depict the graph using matplotlib.<br>
<img width="643" alt="Screen Shot 2023-09-07 at 1 06 44 am" src="https://github.com/amalseby/python1/assets/60167060/b1b75433-e03f-4454-b487-caaa0a8fd666">

#Best-selling product & Why?
*Determine the sum of the "Quantity Ordered" by grouping by "Product".<br>
*Visual representation of the Quantity Ordered for each Product.<br>
<img width="671" alt="Screen Shot 2023-09-07 at 1 07 39 am" src="https://github.com/amalseby/python1/assets/60167060/6403dc64-4350-4632-b6d6-c7acf4f94a2e">
* Let us also see a graphic representation of the Prices for each product grouped by Product.

<img width="697" alt="Screen Shot 2023-09-07 at 1 08 26 am" src="https://github.com/amalseby/python1/assets/60167060/20e69c56-5c9d-4df4-94b2-ea5268570c7e">

# What products are most often sold together?

*Group the product by the Order ID to know which products were sold together.<br>
*Find the duplicate values of the “Order ID” by using the .duplicated() method.<br>
*Using .transform() method, create a new column called "Grouped" to combine values from multiple rows into one.<br>
*Drop the duplicates created when products were merged for each order ID.<br>
*Display the top 5 products most often sold together.<br>
<img width="1090" alt="Screen Shot 2023-09-07 at 1 09 24 am" src="https://github.com/amalseby/python1/assets/60167060/76913ffe-0456-45c2-8e92-e266ee0fbb87">

# Conclusion
*The analysis above clearly illustrates that month 12 (December) boasts the maximum sales in 2019 with roughly $9,226,886.<br>
*According to the graph, San Francisco has the largest number of sales.<br>
*The optimum time to display advertising to increase the probability of buyers purchasing the product/s is shortly before 12 pm and/or right before 7 pm.<br>
*The top selling product is 'AAA Batteries (4-pack)'. The top selling products seem to have a correlation with the price of the product. The cheaper the product, higher the quantity ordered and vice versa.




