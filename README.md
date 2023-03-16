# Amazon-Vine-Analysis

## Purpose
This assignment is a technical analysis challenge that requires students to work with Amazon reviews written by members of the paid Amazon Vine program. The project involves using PySpark to perform the ETL process, extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I determine if there is any bias toward favorable reviews from Vine members in the dataset using PySpark, Pandas, and SQL.

## Results

A total of 94 Paid Reviews
A total of 54,0471 Un-Paid Reviews

48 Paid reviews were 5 stars
15,663 Non-Paid reviews were 5 stars

51.1% of the Paid reviews were 5 stars
38.7% of the Un-Paid reviews were 5 stars

A snippet of the code used to determine the values above can be seen here:
![image](https://user-images.githubusercontent.com/102545401/225738539-a4ebec43-8328-4699-a0b1-6ef8fc12f8ee.png)

## Summary
The percentages calculated above suggest that there is a positivity bias among the reviews in the Vine program. This analysis only focuses on the five star reviews and does not account for other reviews that are made. In total there are over a millions five star reviews in the dataset. IT would be best to see the correnaltion across all reviews to get a more accurate picture of the data. 
