--Business Problem:
In this project, we delve deep into the thriving sector of online retail by analyzing a transactional dataset from a UK-based retailer, available at the UCI Machine Learning Repository.
This dataset documents all transactions between 2010 and 2011. Our primary objective is to amplify the efficiency of marketing strategies and boost sales through customer segmentation. 
We aim to transform the transactional data into a customer-centric dataset by creating new features that will facilitate the segmentation of customers into distinct groups using the K-means clustering algorithm.
This segmentation will allow us to understand the distinct profiles and preferences of different customer groups. 
Building upon this, we intend to develop a recommendation system that will suggest top-selling products to customers within each segment who haven't purchased those items yet, ultimately enhancing marketing efficacy and fostering increased sales.

--Objectives:
Data Cleaning & Transformation:
Clean the dataset by handling missing values, duplicates, and outliers, preparing it for effective clustering.

Feature Engineering: 
Develop new features based on the transactional data to create a customer-centric dataset, setting the foundation for customer segmentation.

Data Preprocessing: 
Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process.

Customer Segmentation using K-Means Clustering: 
Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.

Cluster Analysis & Evaluation: 
Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.

Recommendation System: Implement a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to boost sales and marketing effectiveness.

---Range of attributes:

InvoiceNo: This is an object data type column that contains the invoice number for each transaction. Each invoice number can represent multiple items purchased in a single transaction.
StockCode: An object data type column representing the product code for each item.
Description: This column, also an object data type, contains descriptions of the products. It has some missing values, with 540,455 non-null entries out of 541,909.
Quantity: This is an integer column indicating the quantity of products purchased in each transaction.
InvoiceDate: A datetime column that records the date and time of each transaction.
UnitPrice: A float column representing the unit price of each product.
CustomerID: A float column that contains the customer ID for each transaction. This column has a significant number of missing values, with only 406,829 non-null entries out of 541,909.
Country: An object column recording the country where each transaction took place.
From a preliminary overview, it seems that there are missing values in the Description and CustomerID columns which need to be addressed. The InvoiceDate column is already in datetime format, which will facilitate further time series analysis. We also observe that a single customer can have multiple transactions as inferred from the repeated CustomerID in the initial rows.

The next steps would include deeper data cleaning and preprocessing to handle missing values, potentially erroneous data, and to create new features that can help in achieving the project goals.

