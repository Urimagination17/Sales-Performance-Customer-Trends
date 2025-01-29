### **** Sales-Performance-Customer-Trends **** ###

## **Overview**
This project involves advanced SQL queries and analytics on the `classicmodels` database. The queries focus on revenue analysis, customer insights, employee performance, and product trends using aggregate functions, joins, and window functions.

## **Database Tables Used**
- **customers**: Contains customer details.
- **orders**: Stores order information.
- **orderdetails**: Includes item-level details for each order.
- **employees**: Lists employee details.
- **offices**: Stores office location details.
- **products**: Contains product information.
- **productlines**: Defines categories of products.

## **Key Analysis Performed**
### **1. Revenue and Sales Analysis**
- Total revenue generated per office.
- Top 5 products by total sales revenue.
- Cumulative sales revenue per product by order date.

### **2. Employee Performance Analysis**
- Top 5 employees managing the highest number of customers.
- Employee ranking based on total revenue generated.
- Revenue contribution percentage per employee.

### **3. Customer Insights**
- Customers who ordered from all product lines.
- Customers whose orders contain both the cheapest and most expensive products.
- Customers who have never ordered from the ‘Classic Cars’ product line.

### **4. Window Function Queries**
- Running total of payments received per customer.
- Ranking of products within each product line based on total revenue.
- Identifying the top customer in each month based on order count.

## **How to Use**
1. Load the `classicmodels` database in MySQL.
2. Execute the SQL queries in `queries.sql` using MySQL Workbench or any SQL execution tool.
3. Modify queries as needed to perform custom analysis.

## **Requirements**
- MySQL (Recommended version: 8.0+)
- MySQL Workbench or any SQL IDE.
