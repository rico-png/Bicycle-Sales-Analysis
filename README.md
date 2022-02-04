# Bicycle-Sales-Analysis


# Project Introduction

In this project I will be examining a dataset that contains the sales of bicycle parts across 6 countries which includes United states, Australia, Canada, United Kingdom, 
Germany and France. I will use python as my analysis tool and I hosted my code on Jupyter notebook.  In the course of this, I will collect data, carry out data wangling, 
perform analysis and visualizations to better understand our dataset, create insights and make recommendation.



# Data Review

The Bicycle sales dataset contains 113,036 rows and 18 columns. The content of the dataset includes parts by parts of of bicycle sold across all the 6 countries.
The columns include
    Date – The date format on our date column is DD-MM-YYYY, represents the day,month and year.
    Customer_Age – Represents the customers age.
    Age_Group – Represents a number of people of similar age classed together
    Customer_Gender –  customer’s Gender  was segmented into Male or Female
    State – Represents territory where the products where traded
    Product_Category – is a group of similar products that share similar characteristics.
    Sub_Category – A reduced or subdivision of the Product Category
    Product – it is the item for sale.
    Ordered_Quantity – Quantity Of products a buyer is willing to pay for
    Unit_Cost – Represents the total expenditure incurred to produce,store, and sell one unit of a product.
    Unit_Price – Is the price for one item or product
    Profit – financial Gain on product sales received when revenue surpasses cost and expenses  
    Cost – amount spent in the production of the products
    Revenue – amount generated from the sales of products

I added the Sales column  to assist us examine the sales of different products and how successful the product were.


# Data Extraction.

I extracted my dataset from a github(https://github.com/Python-World/python-mini-projects) repository, I forked and pulled the dataset into my local repository so 
I could have a very good look at the columns in my machine then used a built in python function( pd.read_csv) to extract into my jupyter notebook. 
However, you can also use a web scraping method for this. Simply import pandas (import pandas as pd) and NumPy (import numpy as np) and then a simple syntax 
(df = pd.read_html(‘url of the dataset’)) can also get you the dataset.



# Data Cleaning and Preparation.

After data extraction,


Saved the data in DataFrame using pd.DataFrame(“dataset”) and used dataset.shape to know the number of            
rows and columns contained in my dataframe

Checked for null values across using ‘dataset’.isnull().sum()

Viewed the details of the dataset using dataset.head()—this automatically shows you the 5 rows of your dataset.
 
Also used .info(), .dtypes and .describe to know the details, the data type and the statistical analysis of our dataset respectively.

I added SALES column  by multiplying the Order_Quantity column by the Unit price.






# Please look up my 'EXECUTIVE SUMMARY' FOR A DETAILED ANAYSIS.



