# Designing-a-Database
This repository contains SQL script for creating a relational and non relational databases.

This project provides SQL scripts to establish relational and non-relational databases for an e-commerce platform. The relational model (using SQL) defines three tables: Customer, Product, and Orders to store customer information, product details, and order history respectively. The non-relational model (using MongoDB) utilizes document-based storage, where each customer, product, and order is represented as a JSON-like document, allowing for flexible data structures and accommodating evolving requirements of the e-commerce platform.

The document model in MongoDB offers several advantages:

Flexibility: It can easily handle variations in product attributes, customer information, and order details.

Nested Data: It allows embedding related information (e.g., order items within an order document) to improve query performance.

Schema Evolution: Changes to the data model can be made without significant disruptions to the database structure.

Scalability: MongoDB is designed for horizontal scalability, making it suitable for handling large amounts of data and high traffic.

Performance: MongoDB excels at handling reads and writes, making it a good choice for real-time applications.
