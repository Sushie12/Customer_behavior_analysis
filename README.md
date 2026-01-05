CUSTOMER BEHAVIOR ANALYSIS:
This project analyses shopping behavior using transactional data across various product categories. 
The goal is to uncover insights into spending patterns,product preferences and other shopping behavior among customers of various backgrounds.

-Dataset: Customer_Shopping_Trends imported from Kaggle.

-Dataset Summary:
Rows: 3,900 
Columns: 18
Key Features:
     i.   Customer demographics (Age, Gender, Location, Subscription Status).
     ii.  Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color).
     iii. Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of 
          Purchases, Review Rating, Shipping Type).
     iv.  Missing Data: 37 values in Review Rating column.

-Exploratory Data Analysis Using Python:
  Environment: Jupyter Notebook
Understood the data better using data.info() and data.describe().
Handled missing values by filling it with median values.
Performed binning and created age_groups column.
Converted categorical columns to numerical i.e. Frequency_purchases(Weekly,monthly,Quarterly) to Purchase_frequency_days(7,30,90).

-Analysis using SQL:
  Environment- MySQL Workbench.
Conducted queries for:
1.Revenue by gender
2.High spending discount users
3.Top 5 products by rating
4.Subscribers v.Non-subscribers...and more.

-Data Visualisation:
  Environment: Microsoft Power BI
Created a dashboard to present insights visually.
  
  
  
  
  
  
