## Start Your Day With Coffee - Coffee Shop Sales Analysis

**Project Objective:**

This project analyzes retail sales data from a coffee shop to gain actionable insights that will enhance its performance.

![Coffee Shop Sales Dasboard](https://github.com/user-attachments/assets/418f0dcd-502c-486e-82ee-54e980802b1b)


**Dataset Used:** <a href="https://github.com/angelinanayak000/Coffee-Shop-Sales_Analysis/blob/main/Coffee%20Shop%20Sales.xlsx">Download Dataset<a/>

The dataset includes information on sales transactions, including order details (date, time, products, quantities, prices), customer information (if available), and store location.

**My Project:** <a href="https://github.com/angelinanayak000/Coffee-Shop-Sales_Analysis/blob/main/Coffee%20Shop%20Sales%20Data%20Analysis.xlsx">View and Interact with Dashboard<a/>


**Questions (KPIs):**

*   **How do sales vary by day of the week and hour of the day?**
    *   Sales peak during morning hours (6-10 AM) and again in the evening (6 PM to 8 PM).
    *   Monday, Thursday, Friday has the highest order volume.

*   **Are there any peak times for sales activity?**
    *   Yes, peak sales times are observed between 6-10 AM and 6 PM - 8 PM.

*   **What is the total sales revenue for each month?**
    *   Highest in June - $1,63, 835

*   **How do sales vary across different store locations?**
    *   Hell's Kitchen location has the highest footfall, indicating higher sales potential.

*   **What is the average price/order per person?**
    *   $4.61

*   **Which products are the bestselling in terms of quantity and revenue?**
    *   Barista Espresso
    *   Brewed Black Tea
    *   Gourmet Coffee
    *   Hot Chocolate
    *   Brewed Chai Tea

*   **How do sales vary by product category and type?**
    *   Coffee and Tea categories dominate sales.

**KPIs:**

*   **Sales:** Total sales revenue: $6,87,594.00
*   **Footfall:** Total number of customers: 1,49,116
*   **Average Bill per Person:** $4.61
*   **Average Order per Person:** 1

**Process:**

1.  **Data Cleaning:**
    *   Used Power Query to clean and transform data:
        *   Extracted month, year, day of the week, and hour from date and time columns.
        *   Removed duplicates and handled missing values.
        *   Created a new column for "Order Size" based on quantity.
        *   Cleaned and standardized product names and descriptions.
    *   Created a new column for "Total Price" by multiplying quantity by unit price.

2.  **Data Analysis:**
    *   Used Pivot Tables to analyze data:
        *   Sales by day of the week and hour.
        *   Total sales revenue by month.
        *   Sales by store location.
        *   Sales by product category and type.
        *   Top 5 bestselling products.
        *   Customer count by day of the week.
    *   Created charts:
        *   Pie chart for sales by category.
        *   Line chart for hourly order quantity.
        *   Column chart for footfall by store location.
        *   Pie chart for size distribution of orders.
        *   Column chart for orders on weekdays.

3.  **Data Modeling:**
    *   Used Power Pivot to create measures:
        *   **Sales:** Sum of total bills.
        *   **Footfall:** Distinct count of transaction IDs.
        *   **Average Bill per Person:** Sales / Footfall.
        *   **Average Order per Person:** Sum of quantity / Footfall.

**Insights:**

*   **Peak Sales Times:** Sales peak during morning hours (6-10 AM) and again in the evening (6 PM to 8 PM).
*   **Weekday Sales:**  Monday, Thursday, Friday have the highest order volume.
*   **Monthly Sales:** Highest in June - $1,63, 835
*   **Top Selling Products:** 
    *   Barista Espresso
    *   Brewed Black Tea
    *   Gourmet Coffee
    *   Hot Chocolate
    *   Brewed Chai Tea
*   **Category Distribution:** Coffee and Tea categories dominate sales.
*   **Footfall by Location:** Hell's Kitchen location has the highest footfall.
*   **Order Size Distribution:** 
    *   Regular: 30%
    *   Large: 31%
    *   Not Defined: 30%
    *   Small: 9%

**Recommendations:**

*   **Capitalize on Peak Hours:** Increase staffing and optimize operations during peak hours (6 PM to 8 PM) and during the morning peak.
*   **Weekday Promotions:** Consider offering weekday specials to attract customers during off-peak hours.
*   **Focus on High-Performing Products:** Promote and cross-sell top-selling products like Barista Espresso, Brewed Black Coffee, and Gourmet Coffee.
*   **Customer Relationship Management:** Analyze customer data to identify repeat customers and implement loyalty programs.
*   **Location Optimization:** Analyze footfall data to identify potential for expansion or improvement in service at the Hell's Kitchen location.
*   **Order Size Optimization:** Encourage customers to order larger sizes (Large or Regular) to increase average order value.

**Dashboard Insights:**

The dashboard provides a dynamic view of sales performance across different dimensions:

*   **Sales by Category:** Visualizes the sales contribution of each product within each category.
*   **Profit by Year:** Tracks the profit trend over the years for each product category.
*   **Sales by State:** Maps the geographical distribution of sales across different states.
*   **Customer Count:** Shows the growth in customer base over the years.
*   **Top 5 Customers:** Highlights the top-performing customers.
*   **Monthly Sales:** Illustrates the seasonal sales trends.

This analysis provides valuable insights into the company's sales performance and can be used to inform strategic decisions related to product development, marketing, and customer engagement.
