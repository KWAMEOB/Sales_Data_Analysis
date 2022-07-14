# Sales_Data_Analysis

# Background
Sample Sales Data, Order Info, Sales, Customer, Shipping, etc., Used for Segmentation, Customer Analytics, Clustering and More. Inspired for retail analytics. This was originally used for Pentaho DI Kettle, But I found the set could be useful for Sales Simulation training. 

Originally Written by María Carina Roldán, Pentaho Community Member, BI consultant (Assert Solutions), Argentina. This work is licensed under the Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License. Modified by Gus Segura June 2014.


# ASK

## Business Task

### Do certain months experience an increase in revenue? 

What was the best month for sales? 

How much was earned in that best month? 

Which Quarter is best for each product line?

### Which city and country has the highest sales? 

What city had the highest sales?

Which country has the highest sales?

### Which are the top selling items by state or country or territory? 

What product sold the most?


# PREPARE

## Data Used:

Gus Segura’s Sample Sales Data [https://lnkd.in/gNr4nrbA] 

## Data summary:

Sample Sales Data, Order Info, Sales, Customer, Shipping, etc., Used for Segmentation, Customer Analytics, Clustering and More. Inspired for retail analytics. This was originally used for Pentaho DI Kettle, But I found the set could be useful for Sales Simulation training. 

Originally Written by María Carina Roldán, Pentaho Community Member, BI consultant (Assert Solutions), Argentina. This work is licensed under the Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License. Modified by Gus Segura June 2014.


# PROCESS

For the sales anaylsis, we will be using the Sales Dataset (sales_data_sample.csv)

1.	We will use to google sheets to clean the data and lookout for any abnormalizes.

•	Checked for duplicate data and remove duplicates
Data -> Data cleanup -> Remove duplicates

•	Checked to see if there are any null entries

2.	After the data cleaning, there were no duplicates and also no null entries.

3.	Based on the task for the project, you will add and drop some columns to be able to ask the business task.

![image](https://user-images.githubusercontent.com/106181129/179027571-2b3928fa-cd92-49b6-9aa6-09de1bffb052.png)


# ANALYZE

After the data cleaning, I opted to use SQL(BigQuery) in the data analysis

•	What was the best month for sales? How much was earned in that best month?
This will show the best month in Total Sales and how much was earned in each month.

![image](https://user-images.githubusercontent.com/106181129/179028019-e57245b6-b4b3-4864-aea6-f2a5a02bf5ad.png)

![Monthly Sales](https://user-images.githubusercontent.com/106181129/179028309-6fd0cafc-a149-478e-ade3-132d3eb07ea7.png)

•	What city and country had the highest sales ?

This will show the city and country which had the highest sales in all products.

![image](https://user-images.githubusercontent.com/106181129/179029064-e8dd79b6-e66d-4eed-99e3-cba681b03ce0.png)

![Sales by City](https://user-images.githubusercontent.com/106181129/179029148-0e1de382-e160-4932-983d-cb258cb1ea86.png)

Which country has the highest Sales?

![image](https://user-images.githubusercontent.com/106181129/179029413-7fb30de3-94e4-4be4-a915-db7a40e6e39e.png)

![Sales by Country](https://user-images.githubusercontent.com/106181129/179029503-e6e29004-805b-469e-a93c-7bf1d7bc4f93.png)

•	Which Quarter was best for each product line ?

This will show the number of Sales in each Quarter for each Product and the results will show the best Quarter for each Product

![image](https://user-images.githubusercontent.com/106181129/179029892-1261c0a7-2664-4568-9991-9a8b57d94429.png)


•	What product sold the most ?

This will show which Product in the Product line has the highest Sales.

![image](https://user-images.githubusercontent.com/106181129/179030153-f47d0a67-5c8a-47d6-a094-7ca0c870e368.png)

![Product by Sales](https://user-images.githubusercontent.com/106181129/179030227-a789258d-e5cf-46c3-aca3-4f4035ff0594.png)


# SHARE

## Supporting with visualizations and key findings

https://public.tableau.com/authoring/ExecutiveSalesSummary_16577370642950/SalesDashBoard#1

## A summary of your analysis

•	From the analysis above, we noticed that November is the best month in terms of sales and with sales value of around $2,118,885.67. 

•	The city with the highest sales was Madrid with sales of $1,082,551.44 and the country with the highest sales was the USA with sales value of $3,627,982.83

•	The highest sales for all the products in the product line happened in Q4(Quarter 4). That means, Q4 is the most important Quarter in terms of sales for any product line.

•	From the analysis, the Classic cars sold most and the least sold product in the product line are Trains.


# ACT

## Recommendations

•	Management should make sure there are more products of each product in the product line in the Q4 since all the products has huge sales in the Q4 and most sales were also recorded in the Q4.

•	Management should increase the availability of Classic cars and Vintage cars since they were most sought-after products in the product line. Vintage cars came in as a the second most product in the product line.



