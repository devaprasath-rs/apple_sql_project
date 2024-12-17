# Apple Retail Sales Analysis SQL Project 🛠️🍎

## 📘 Project Overview
This project showcases advanced SQL querying techniques through the analysis of over 1 million rows of Apple retail sales data. The dataset includes information about **products, stores, sales transactions, and warranty claims** across various Apple retail locations worldwide.  
It involves solving questions of varying complexity to extract actionable insights, demonstrating the power of SQL in handling and analyzing large datasets.

---

## 📂 Database Schema
The project uses the following five main tables:

1. **`stores`**: Contains information about Apple retail stores.  
   - `store_id`: Unique identifier for each store.  
   - `store_name`: Name of the store.  
   - `city`: City where the store is located.  
   - `country`: Country of the store.  

2. **`category`**: Holds product category information.  
   - `category_id`: Unique identifier for each product category.  
   - `category_name`: Name of the category.  

3. **`products`**: Details about Apple products.  
   - `product_id`: Unique identifier for each product.  
   - `product_name`: Name of the product.  
   - `category_id`: References the `category` table.  
   - `launch_date`: Date when the product was launched.  
   - `price`: Price of the product.  

4. **`sales`**: Stores sales transaction details.  
   - `sale_id`: Unique identifier for each sale.  
   - `sale_date`: Date of the sale.  
   - `store_id`: References the `stores` table.  
   - `product_id`: References the `products` table.  
   - `quantity`: Number of units sold.  

5. **`warranty`**: Contains warranty claim details.  
   - `claim_id`: Unique identifier for each warranty claim.  
   - `claim_date`: Date the claim was made.  
   - `sale_id`: References the `sales` table.  
   - `repair_status`: Status of the claim (e.g., Paid Repaired, Warranty Void).  

---

## 🎯 Project Objectives
The project is divided into three levels of questions to test SQL skills of increasing complexity:

### Easy to Medium (10 Questions)
1. Find the number of stores in each country.  
2. Calculate the total units sold by each store.  
3. Identify the sales count in December 2023.  
4. Determine stores with no warranty claims.  
5. Calculate the percentage of "Warranty Void" claims.  
6. Identify the store with the highest total units sold last year.  
7. Count the unique products sold last year.  
8. Find the average price of products in each category.  
9. How many warranty claims were filed in 2020?  
10. For each store, identify the best-selling day based on the highest quantity sold.  

### Medium to Hard (5 Questions)
11. Identify the least selling product in each country for each year based on total units sold.  
12. Calculate how many warranty claims were filed within 180 days of a product sale.  
13. Determine how many warranty claims were filed for products launched in the last two years.  
14. List the months in the last three years where sales exceeded 5,000 units in the USA.  
15. Identify the product category with the most warranty claims filed in the last two years.  

### Complex (5 Questions)
16. Determine the percentage chance of receiving warranty claims after each purchase for each country.  
17. Analyze the year-by-year growth ratio for each store.  
18. Calculate the correlation between product price and warranty claims for products sold in the last five years, segmented by price range.  
19. Identify the store with the highest percentage of "Paid Repaired" claims relative to total claims filed.  
20. Write a query to calculate the monthly running total of sales for each store over the past four years and compare trends during this period.  

### Bonus Question
- Analyze product sales trends over time, segmented into key periods: from launch to 6 months, 6-12 months, 12-18 months, and beyond 18 months.

---

## 🛠️ Project Focus
This project focuses on developing and showcasing the following SQL skills:
- **Complex Joins and Aggregations**: Demonstrating the ability to perform complex SQL joins and aggregate data meaningfully.  
- **Window Functions**: Using advanced window functions for running totals, growth analysis, and time-based queries.  
- **Data Segmentation**: Analyzing data across different time frames to gain insights into product performance.  
- **Correlation Analysis**: Applying SQL functions to determine relationships between variables, such as product price and warranty claims.  
- **Real-World Problem Solving**: Answering business-related questions that reflect real-world scenarios faced by data analysts.  

---

## 📊 Dataset
- **Size**: 1 million+ rows of sales data.  
- **Period Covered**: The data spans multiple years, allowing for long-term trend analysis.  
- **Geographical Coverage**: Sales data from Apple stores across various countries.  

---

## 🚀 Conclusion
Completing this project helped me develop **advanced SQL querying skills**, improved my ability to handle **large datasets**, and provided **practical experience in solving complex data analysis problems** crucial for business decision-making.
