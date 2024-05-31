# Market-Basket-Analysis

# Project OverView
This project aims to provide strategic recommendations for an upcoming category review by conducting a Market Basket Analysis (MBA) to uncover patterns in customer purchasing behavior, with a particular focus on chip products. The analysis will identify frequently bought together items and analyze customer segments, enabling data-driven strategies to optimize product offerings, marketing efforts, and inventory management.


## Problem Statement 
In the competitive landscape of retail, understanding customer behavior and purchasing trends is critical for making informed business decisions. This project aims to provide a strategic recommendation for an upcoming category review by analyzing customer purchasing patterns, with a particular focus on chip products. By examining key metrics and customer segments, the analysis will uncover insights into purchasing behaviors, preferences, and trends, enabling data-driven decision-making to optimize product offerings, marketing strategies, and inventory management.

## Dataset Description

The dataset comprises two main components: Transaction Data and Customer Data. Both datasets contain detailed records of retail transactions, capturing essential information about purchases made by customers.

Transaction Data: This dataset includes information about individual transactions, such as the transaction date, store number, loyalty card number, transaction ID, product number, product name, quantity purchased, and total sales amount.

Customer Data: This dataset includes information about customers such as lifestage,Premium Customers and Loyality Card Number.

## Steps

### 1. Importing Necessary Libraries
We import libraries like pandas, numpy, matplotlib, and seaborn for data manipulation and visualization.

### 2. Loading the Dataset
Load the transaction and customer datasets using pandas.

### 3. Data Preprocessing

#### Checking Data Types
Ensure that data types are correctly set.

#### Converting Date Column to Datetime Format
Convert the 'date' column to a proper datetime format.

#### Checking for Missing Values
Identify any missing values in the datasets.

#### Text Analysis on Product Types
Analyze product names to focus on the chips category.

#### Filtering for Chips Category and Removing Salsa Products
Filter data to include only chips products and exclude salsa products.

#### Checking for Outliers
Identify and handle outliers in the price data.

#### Removing Outliers
Remove outliers based on price.

#### Exploratory Data Analysis (EDA)
Plot transactions over time.

#### Creating New Columns: Pack Size and Brand Name
Extract pack size and brand name from product descriptions.

#### Combining Duplicate Brand Names
Standardize brand names to handle duplicates.

### 4. Customer Data Preprocessing
Ensure customer data is clean by checking data types and handling any missing values.

### 5. Merging Transaction and Customer Data
Merge the transaction data with customer data to create a comprehensive dataset for analysis.

### 6. Customer Segmentation Analysis

#### Who Spends the Most on Chips?
Identify customers who spend the most on chips.

#### Describing Customers by Lifestage and Premium Purchasing Behavior
Analyze spending patterns based on customer lifestage and premium purchasing behavior.

#### Number of Customers in Each Segment
Calculate the number of customers in each segment.

#### Total Chips Bought by Segment
Determine the total number of chips bought by each customer segment.

### Conclusion

Sales have mainly been driven by Budget - older families, Mainstream - young singles/couples, and Mainstream - retirees shoppers. Here's a summary of our key findings:

- **Older Families in the Budget Segment**: This group is the highest spender within the Budget category, indicating that older families tend to purchase chips more frequently or in larger quantities.
- **Young Singles/Couples in the Mainstream Segment**: This group is the highest spender within the Mainstream category. Their high spend on chips is due to their greater numbers compared to other buyer segments. Additionally, mainstream young singles and couples are more likely to pay more per packet of chips, suggesting impulsive buying behavior.
- **Older Singles/Couples**: This group consistently shows high total sales across all three premium customer categories, making them a valuable segment for targeted marketing.
- **Retirees in the Mainstream Segment**: Retirees also show significant spending in the Mainstream category, contributing greatly to overall sales.
- **New Families**: This group tends to have the lowest total sales across most premium customer categories, indicating possibly lower spending or fewer transactions in these segments.

We’ve found that Mainstream young singles and couples are 22.80% more likely to purchase Tyrrells chips compared to the rest of the population. This indicates a strong preference for this brand within this segment. 

To enhance the category’s performance, the Category Manager may want to increase the visibility and impulse purchasing of Tyrrells and smaller packs of chips. This could be achieved by off-locating these products in discretionary spaces frequented by young singles and couples, such as near checkout counters or in high-traffic areas of the store.

By targeting these high-value segments and leveraging their purchasing behaviors, we can drive further sales growth and improve overall category performance.
