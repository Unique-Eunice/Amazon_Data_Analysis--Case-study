# Amazon Data Analysis

### Overview
This data analysis project involves cleaning, transforming, and analyzing Amazon product data (product and customer review data) to generate insights that guides product improvement, marketing strategy, and customer engagement.

### Data Sources

Amazon data: The primary dataset used for this analysis is the dataset scaraped from "Amazon product pages" containing detailed information about Products and customer review.

### Tools and Technologies

- Microsoft Excel- Data cleaning, Pivot Tables, Dashboard [Download_here](https//microsoft.com)
- Git & GitHub for version control.

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values and duplicate.
3. Clean complex product category hierarchies for easier analysis.
4. Simplify product names for better reporting.
5. Data cleaning and formating.

### Exploratory Data Analysis (EDA)
EDA involvoed exploring the Product and Review data to answer key questions, such as:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200,
₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

### Data Analysis
``` Excel
= Trim ( Product_Name,25)
```

### Results And Findings

The analysis results are summarized as follows:
- Price analysis revealed that products (greater than $500) accounted for the largest share of listings.
- Discount analysis showed that **Computer and Accessories** and **Home improvements** had the highest average discounts, making them competitive in pricing.
- Rating distribution indicated that over 70% of products had ratings above 4.1, highlighting overall customer satisfaction.
- The top-rated products were mainly clustered in categories like **Computers and accessories** and **Cables**.
- Fewer products had less than 1000 reviews.
- Analysis showed no strong correlation between discount price and higher product rating, indicating price is not always a quality indicator.
- Grouping products into price ranges and analyzing sales potential based on rating and discounts helped identify promising product segments.

### Recommendations
- **Review Low-Rated Discounted Products:** Investigate and improve product quality in categories where heavy discounts coincide with low ratings.
- **Optimize Mid-Range Pricing Strategies:** Continue leveraging the less than $500 price band, which dominates the product listings and reflects strong consumer interest.
- **Enhance Discount Strategies:** Utilize competitive discounting in high-performing categories to boost sales, while avoiding reliance on discounts to mask quality issues.
- **Regular Product Performance Reviews:** Monitor rating trends, price adjustments, and discount impacts periodically to ensure ongoing competitiveness.
- **Bundle Product Offerings:** Explore bundling complementary products in top categories to increase average order value and customer satisfaction. (e.g Amazon basic flexible Premium HDMI cable)
- **Leverage Customer Feedback:** Encourage and analyze customer reviews to identify areas for product and service improvements.

### Limitations

I had to replace some missing values with assumed values and i also had to remove some data that would have affected the accuracy of my analysis. There are might still be a few outliers, However, there is a linear relationship dicount price and rating count.

### References
1. Incubator hub
2. Her Data Project
3. Data Camop
4. Chatgpt
   





