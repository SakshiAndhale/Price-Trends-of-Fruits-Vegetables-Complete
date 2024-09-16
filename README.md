# Retail Price Analysis of Fruits and Vegetables Dataset

## Overview

This project involves two datasets that contain detailed information on the **retail prices of various fruits and vegetables**. Each dataset provides insights into pricing, yield, cup-equivalent size, and value offered by different fruits and vegetables across various forms (fresh, canned, frozen, dried). The goal of this project is to extract meaningful insights and help retailers make informed decisions regarding inventory, pricing, and marketing strategies.

## Table of Contents

1. [Objective](#objective)
2. [Dataset Overview](#dataset-overview)
3. [Data Cleaning](#data-cleaning)
4. [Visualizations](#visualizations)
5. [Key Insights](#key-insights)
6. [Conclusion](#conclusion)

## Objective

The primary objective of this project is to analyze the pricing structure of both fruits and vegetables in various forms. By doing so, we aim to provide business insights into:

- **Which fruits and vegetables are the most expensive?**
- **Which fruits and vegetables are the most affordable?**
- **How does yield vary between different forms (fresh, canned, frozen, dried)?**
- **What is the best price-to-cup equivalent size ratio for fruits and vegetables?**
- **Which form (fresh, canned, frozen, dried) is the most economical?**

The analysis provides insights into consumer trends, retail pricing strategies, and value optimization across the produce industry.

## Dataset Overview

The datasets contain the following columns for both fruits and vegetables:

- **Name:** The specific fruit or vegetable (e.g., Apple, Carrots, Broccoli, Spinach).
- **Form:** Indicates whether the fruit or vegetable is fresh, frozen, canned, dried, or juiced.
- **Retail Price:** The price of the item per pound or unit.
- **Retail Price Unit:** The measurement unit for the price (e.g., per pound, per unit).
- **Yield:** The percentage of usable parts of the fruit or vegetable after cooking or preparation.
- **Cup Equivalent Size:** The size per cup-equivalent serving of the item.
- **Cup Equivalent Price:** The price for one cup-equivalent serving.

The fruits dataset offers detailed pricing on commonly consumed fruits in different forms, while the vegetable dataset focuses on pricing data across various vegetable forms.

## Data Cleaning

To ensure the datasets were suitable for analysis, we applied several data cleaning methods, including:

1. **Handling Missing Values:**  
   Missing values in critical columns like retail price, yield, and cup-equivalent size were filled using the **mean value** for similar fruits and vegetables in the same form. For example, if a price for canned peaches was missing, it was replaced by the average price of other canned fruits.

2. **Rounding Numerical Values:**  
   The retail price and yield data contained excessive decimal points (up to four decimal places), which were rounded to **one decimal place** to make the dataset more readable and precise.

3. **Standardizing Categorical Data:**  
   Inconsistent labeling, such as using "fresh" and "Fresh," was standardized for all entries, ensuring uniformity and more accurate comparisons.

4. **Data Type Corrections:**  
   We also corrected the data types for categorical variables like `Form`, ensuring they are properly coded for analysis.

## Visualizations

To answer the key questions, we created several visualizations, each focusing on different aspects of the datasets:

1. **Top 5 Most Expensive Fruits and Vegetables:**  
   A bar chart showcasing the top 5 items with the highest retail prices per pound or unit.

2. **Top 5 Most Affordable Fruits and Vegetables:**  
   A bar chart highlighting the top 5 most affordable items.

3. **Yield Distribution by Form (Fresh, Canned, Frozen, Dried):**  
   A pie chart showing how yield is distributed across different forms of fruits and vegetables.

4. **Best Price-to-Cup Equivalent Size Ratio:**  
   A scatter plot examining which fruits and vegetables offer the best value in terms of price per cup-equivalent size.

5. **Comparison of Fruit and Vegetable Forms:**  
   A stacked bar chart comparing the retail price across different forms (fresh, canned, frozen, dried) of fruits and vegetables.

6. **Cup-Equivalent Size Distribution:**  
   A bar chart comparing the cup-equivalent size for different fruits and vegetables to identify which offer the most substantial portions.

## Key Insights

From our analysis, we derived several important insights:

1. **Most Expensive Items:**  
   - **Asparagus** is the most expensive vegetable, priced at **$6.0 per pound**.
   - **Avocados** are among the most expensive fruits, priced at **$5.8 per pound**.

2. **Most Affordable Items:**  
   - **Carrots** and **Onions** are the most affordable vegetables at **$1.0 per pound**.
   - **Bananas** and **Apples** are the most affordable fruits, both priced at around **$1.2 per pound**.

3. **Yield Distribution:**  
   - **Fresh vegetables** have the largest share of yield, at **40.07%**, followed by **Frozen (22.57%)**, and **Canned (15.85%)** vegetables.
   - For fruits, **Juiced and Fresh fruits** contribute the most yield, making them the best value for customers in terms of portion size.

4. **Best Value:**  
   - **Carrots** and **Cabbage** provide the best price-to-cup equivalent size ratio among vegetables, offering substantial portions at low cost.
   - Among fruits, **Bananas** and **Oranges** provide the best value, making them ideal for budget-conscious consumers.

5. **Comparison of Forms:**  
   - **Fresh fruits and vegetables** generally offer better value in terms of yield and cup-equivalent size than their canned or dried counterparts.  
   - **Dried fruits** like **Raisins** are expensive per unit, but offer a long shelf life, which may justify the price.

## Conclusion

This analysis has revealed significant insights that can aid **retailers** in making data-driven decisions regarding **pricing**, **stock management**, and **marketing strategies** for fruits and vegetables.

- **High-priced items** like Asparagus and Avocados should be positioned as premium products.
- **Affordable items** like Bananas, Carrots, and Onions should be marketed as cost-effective, value-driven products.
- **Fresh produce**, which offers the highest yield and better price-to-cup equivalent size ratios, should be a focal point for retailers looking to provide value.
- **Dried and Canned forms** are ideal for long-term storage, though they come at a higher cost per unit, which should be taken into account when setting pricing strategies.

Through these insights, retailers can optimize their offerings to better meet the diverse needs of their customers, from budget-conscious shoppers to those seeking premium products.

## Technologies Used

- **Power BI** (for dashboard creation)
- **Excel** (for initial data exploration)

