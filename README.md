# Optimized-MySQL-Relational-Database-for-Brazilian-E-Commerce

## Introduction
This project involves the design and analysis of an e-commerce database schema. The database stores information about customers, orders, payments, reviews, products, sellers, and the relationships between them.

## Key Features
1. **Database Schema Design**: The project includes the creation of seven tables with appropriate columns and relationships to capture the essential data for an e-commerce platform.
2. **SQL Queries**: The project provides several SQL queries to extract meaningful insights from the database, such as:
   - Total sales for each product category
   - Top 10 customers by single transaction spend
   - Most used payment type and maximum amount spent for each payment type
   - Number of orders with review score less than 3

## Database Tables
The database consists of the following tables:

1. **Customer_T**: Stores customer information, including customer ID, first name, last name, zip code, city, state, and phone.
2. **Order_T**: Stores order information, including order ID, customer ID, order price, order status, approval date, delivery dates, and estimated delivery date.
3. **Payment_T**: Stores payment information for each order, including payment ID, order ID, payment sequence, payment type, number of installments, and payment value.
4. **Review_T**: Stores review information for each order, including review ID, review score, review date, and order ID.
5. **Product_T**: Stores product information, including product ID, category, name, description, quantity, weight, length, height, and width.
6. **Seller_T**: Stores seller information, including seller ID, name, phone, zip code, city, and state.
7. **Info_T**: Stores the relationship between orders, products, and sellers, including order ID, product ID, and seller ID.

## Libraries Used
The project utilizes the following libraries:
- **SQL**: For creating the database schema and executing the queries

## How to Use
1. Create the database schema by running the SQL script in the `Project_Schema.sql` file.
2. Insert sample data into the database by running the SQL script in the `Project_Data.sql` file.
3. Run the queries provided in the `Project_Query.sql.pdf` file to analyze the data.

## Results
The provided SQL queries demonstrate the analysis of the e-commerce database, including:
- Calculating the total sales for each product category
- Identifying the top 10 customers by single transaction spend
- Determining the most used payment type and the maximum amount spent for each payment type
- Counting the number of orders that have a review score less than 3

## Future Improvements
- Expand the database schema to include additional entities and relationships
- Implement more complex queries to extract further insights from the data
- Automate the data insertion and query execution process
- Integrate the database with a front-end application for user interaction

## References
1. SQL documentation and resources
