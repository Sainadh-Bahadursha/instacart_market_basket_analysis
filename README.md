# instacart_market_basket_analysis
## Project Description
> Instacart is a grocery delivery company in the United States and Canada. It's service allows customers to order groceries from participaing retailers via a website and mobile app.

> A public Instacart cart dataset from https://www.kaggle.com/competitions/instacart-market-basket-analysis/data has utilised to perform Exploratory Data Analysis and Market Basket Analysis

> Support, Confidence values for each product are generated without using MLXTEND module

## Contents
1. Introduction to Instacart and Market Basket Analysis
2. Importing Python Libraries and Instacart Dataset
3. Basic Desription of Data
4. Exploratory Data Analysis on orders.csv
   1. Visualising the value counts of columns in orders (which have nunique <= 31) using count plot
   2. Descriptive Statistics of orders["days_since_prior_order"] file
   3. Finding the maximum orders done by each user_id, Bar plot between Number of users Vs Max Order Number and other related descriptive statistics
   4. Number of users vs (Day of week, order hour of day, days since prior order)
   5. Heat map between Day_of_Week and Hour_of_day
5. Exploratory Data Analysis on order_products_prior and train stacked file
   1. Vertically stacking the order_products_prior and train
   2. Bar plot between Number of items in cart Vs Number of orders in stacked ordp
   3. Bar plot between products with Reordered = 0 vs Reordered = 1
6. Exploratory Data Analysis on Aisles, Products and Departments
   1. Joining Aisles, products and departments datasets
   2. Total products in Aisle Vs Aisle
   3. Total Aisles in Department Vs Department
   4. Total products in Department Vs Department
7. Exploratory data analysis on merged_df
   1. Merge all the datasets
   2. Total number of product purchases from Aisle Vs Aisle
   3. Total number of product purchases from a Department Vs Department
   4. Number of product purchases heat map between aisle and department
   5. Reorder percentage For Each product
8. Market Basket Analysis
   1. Formulae
   2. Transactions dataframe
   3. Calculating support and frequent itemsets
   4. Generating association rules
   5. Network graph representing product associations
9. Conclusion and Future scope
10. References

## Credits
> This project is organised and developed as one of the SCALER Portfolio Projects.

> Scaler is a transformative learning platform devoted towards assisting tech professionals in upskilling and scaling up their careers.

> I am truly grateful to Brahma Reddy sir and Pankhuri Bansal madam from SCALER for providing clear and helpful suggestions to complete the project.
