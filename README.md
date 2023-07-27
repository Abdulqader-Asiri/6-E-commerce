# 6 - E-commerce
--------------------
![](photo/main.png)
--------------------
## Introduction

E-commerce (electronic commerce) is the buying and selling of goods and services, or the transmitting of funds or data, over an electronic network, primarily the internet. These business transactions occur either as business-to-business (B2B), business-to-consumer (B2C), consumer-to-consumer or consumer-to-business
------------------
## Problem Statement
-	What was the highest Sale in 2020?
-	What is the average discount rate of chairs?
-	What are the highest-selling months in 2020?
-	What is the Profit Margin for each sales record?
-	How much profit is gained for each product?
-	What is the total Profit & Sales by Sub-Category?
-	People from the city/state shop the most?
--------------------------
### TOOLS
- PYTHON
- MICROSOFT EXCEL
----------------------------
## Data Sourcing
The data was in the [Kaggle](https://www.kaggle.com/datasets/abdulqaderasiirii/e-commerce-data) website.

### About the data : 
This is a simple dataset of US online_store from 2020, the dataset contains 3312 rows and 20 columns.
-----------------
## Cleaning & Analysis
-There are no null values so this is a good start.

- Replace the spaces between the names of the columns to underline (_), to make the EDA easy.

- Drop (columns=['row_id', 'order_id' , 'customer_id', 'country' , 'postal_code', 'product_id' ]), because we don’t need it.

- Extract the (months, years) from the (order_data).

### We could discover the following things in the dataset:
-	The highest Sale in 2020 was in (2020-03-23) and its (Copiers) (4 quantity) by (13999.96) and the profit was (6719.9808).

-	The average Discount of Charis is : (0.16737).

-	The highest selling months in 2020 Is:
o	(11) -->(118447.8250)
o	(9) -->(87866.6520)
o	(12) -->(83829.3188)

## Data Transformation
### No need for Transformation.
--------------

## Modeling
### No modeling was required since we just use Python for the analysis.

# Thank you
