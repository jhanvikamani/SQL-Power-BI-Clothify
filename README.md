# SQL-Power-BI-Clothify

PROJECT PROPOSAL

The objective of this project is to gain insights into the Clothify business by quering and analysing the database using SQl and creating interactive visualizations with power BI. The project aims to answer questions related to customer behaviour, distributor performance, inventory management, order trends, and payment analysis. 
Clothify is an imaginary clothing e-commerce database that I created, and the database contains several key tables, including customer, distributor, order, order item, product, product category, inventory, and payment. 

TOOL USED:

  Microsoft SQL Server Management Studio
  POWER BI

METHODOLOGY: 

DATABASE - Clothify

CREATED TABLE :

  1. Customer - it contain customer details which includes customerID, name, email, address, phone-no, gender, age <br>
  2. Distributor - it contain distributor details which includes DistributorID, Name, Email, Address, Phone-No, Gender, Age <br>
  3. Order Table - it contain order details which includes orderID, order date, customerID, status, order-no, total amount <br>
  4. Product Category - it contain details of product category which includes categoryID, name <br>
  5. Product - it contains details of product which includes productID, product name, description, price, distributorID, categoryID <br>
  6. Inventory - it contains details of inventory which includes InventoryID, ProductID, Quantity <br>
  7. Order Item - it contains details of all order items which includes orderitemID, orderitem quantity, price, orderID, productID <br>
  8. Payment - it contains details of payment made by customer inculding tax amount which includes paymentID, payment date, amount, orderID, customerID <br>

INSERTED RECORDS 

PERFORMED ANALYSIS:

CUSTOMER <br>

   How many customers are there in total? <br>
       How many customers are male and female? <br>
       what is the average age of all the female customer? <br>
       How many customer placed the order and among them which customer placed the maximum order? <br>
       What is the distribution of customers by age group? <br>
       what is the lifespan of customer gretaer than 5 months? <br>
       
DISTRIBUTOR <br>

       what is the distribution of distributors by gender? <br>
       which distributor have the highest number of product? <br>
       
ORDER <br>

       How many orders have been placed in total? <br>
       What is the total revenue generated from orders? <br>
       what is the Average Revenue Per order? <br>
       How many orders are in each status category? <br>
       What is the revenue distribution by product category? <br>
       How many order have placed per date by customer detail? <br>
     
PRODUCT <br>

      What is the average price of products? <br>
      what are the top selling product? <br>
      what is the product distribution by category? <br>
      How many products supplied by each distributor? <br>
      What is the total revenue generated per product? <br>
     
Iventory <br>

      How many items are in the inventory for each product? <br>
      Which products have low inventory quantities? <br>
      How many items are in the inventory for each distributor? <br>
      How does the inventory quantity change over time? <br>
      What is the average inventory quantity per product category? <br>
      What is the total value of inventory for each product? <br>
      
ORDER ITEM <br>

      what is the average price of items per order and product? <br>
      How many items are in each order? <br>
      Which products have the highest quantity ordered? <br>
      How does the price of items vary across different orders? <br>
      
PAYMENT <br>

      what is the total amount after 10% Tax? <br>
      how many payment made on each payemnt date? <br>
      
INJECTED DATA INTO POWER BI USING DIRECT QUERY 
 
DATA MODEL

CREATED MEASURE PROFIT USING POWER QUERY

CREATED DASHBOARD USING DIFFERENT FEATURES AND VISUALIZATION OF POWER BI
  
