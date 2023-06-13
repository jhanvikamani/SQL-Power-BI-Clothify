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

  1.Customer - it contain customer details which includes customerID, name, email, address, phone-no, gender, age
  2.Distributor - it contain distributor details which includes DistributorID, Name, Email, Address, Phone-No, Gender, Age
  3.Order Table - it contain order details which includes orderID, order date, customerID, status, order-no, total amount
  4.Product Category - it contain details of product category which includes categoryID, name
  5.Product - it contains details of product which includes productID, product name, description, price, distributorID, categoryID
  6.Inventory - it contains details of inventory which includes InventoryID, ProductID, Quantity
  7.Order Item - it contains details of all order items which includes orderitemID, orderitem quantity, price, orderID, productID
  8.Payment - it contains details of payment made by customer inculding tax amount which includes paymentID, payment date, amount, orderID, customerID

INSERTED RECORDS 

PERFORMED ANALYSIS:

A.CUSTOMER
       How many customers are there in total?
       How many customers are male and female?
       what is the average age of all the female customer?
       How many customer placed the order and among them which customer placed the maximum order?
       What is the distribution of customers by age group?
       what is the lifespan of customer gretaer than 5 months?
       
B.DISTRIBUTOR
       what is the distribution of distributors by gender?
       which distributor have the highest number of product?
       
C.ORDER
       How many orders have been placed in total?
       What is the total revenue generated from orders?
       what is the Average Revenue Per order?
       How many orders are in each status category?
       What is the revenue distribution by product category?
       How many order have placed per date by customer detail?
     
D.PRODUCT
      What is the average price of products?
      what are the top selling product?
      what is the product distribution by category?
      How many products supplied by each distributor?
      What is the total revenue generated per product?
     
E.Iventory
      How many items are in the inventory for each product?
      Which products have low inventory quantities?
      How many items are in the inventory for each distributor?
      How does the inventory quantity change over time?
      What is the average inventory quantity per product category?
      What is the total value of inventory for each product?
      
F.ORDER ITEM
      what is the average price of items per order and product?
      How many items are in each order?
      Which products have the highest quantity ordered?
      How does the price of items vary across different orders?
      
 G.PAYMENT
      what is the total amount after 10% Tax?
      how many payment made on each payemnt date?
      
INJECTED DATA INTO POWER BI USING DIRECT QUERY
 
DATA MODEL

CREATED MEASURE PROFIT USING POWER QUERY

CREATED DASHBOARD USING DIFFERENT FEATURES AND VISUALIZATION OF POWER BI
  
