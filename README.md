

# Pandas Analytics Project

# Introduction - Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, 
to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.


# Project Steps

Aim
Data Sourcing
Data Cleaning
Exploratory Data Analysis
Data Visualization
Conclusion

# Aim

To help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase, by getting valuable and meaningful insight from the sales record data.

# Data Sourcing and description.

Data collected from company XYZ Database.

## Description

#### Invoice ID: Customer Identification number 

#### Branch: Supermarket Branch across the country (A, B, C)
A - Lagos Branch
B - Abuja Branch
C - Port Harcourt Branch

#### City: Supermarket Location

#### Customer Type: Type of customers, Members - Returning customer with membership card, Normal - Customer without membership (could be returning, first-time or walk-in customer)

#### Gender: Customer Gender Information

#### Product line: Product categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

#### Unit Price: Price of each product in Naira

#### Quantity: Number of products purchased by customer

#### Tax: 5% tax fee for customer buying

#### Total: Total price including tax

#### Date: Date of purchase (Supermarket Record available from January 2019 to March 2019)

#### Time: Purchase time (Supermarket Hours - 10am to 9pm)

#### Payment: Payment used by customer for purchase (3 methods are available – Cash, Card and Epay)

#### COGS: Cost of goods sold

#### Gross margin percentage: Gross margin percentage

#### Gross income: Gross income

#### Rating: Customer Satisfaction rating on their overall shopping experience (On a scale of 1 to 10)

# Data Cleaning

Found no missing data, outliers and duplicates.

# Exploratory Data Analysis

Used the head() method to view first few rows of the dataset
Checked the number of rows and columns present in the data using the shape attribute.
Used describe function to generate the statistical summary of the dataframe
Checked the information of the DataFrame using the info method.
Use to_datetime() to convert the date column to datetime
Checked the datatype to confirm if it's in datetime
Extracted the Day, Month, Year & Hour features
Checked for unique hours of sales
Generated the unique values in the categorical columns
Generated the count figure of the categorical values using the value_counts() method.
Created a groupby object with the "City Column", and aggregation function of sum and mean.
Created a table that shows the gross income of each city, and determines the city with the highest total gross income.


# Data Visualization

After exploring the data, i then visualized using seaborn module

# Conclusion

After analyzing company XYZ sales record data, the following insigts were noticed:

1. The unique hours of sales is from 10:00 am to 20:00 pm

2. Port-harcourt have highest gross income.

3. Lagos with highest number of customers

4. Epay as the highset payment method			

5. Fashion Accessories as the most bought product line followed by food and beverages


