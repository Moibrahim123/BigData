# BigData

## Overview 
The objectives of the modules are;
-	Perform ETL of Amazon customer review datasets between Amazon Web Service (AWS) and PostgreSQL.
-	Analyze the trends of reviews by vine (paid) user and non-vine (free) user.

## Resources  
-	Software/ Services: AWS, Google Colab Notebook, pgAdmin 4, Jupyter Lab 
-	Programming Language: PySpark, Python, PostgreSQL 
-	Data Source:

## Objectives
-	Define big data and describe the challenges associated with it. 
-	Define Hadoop and name the main elements of its ecosystem.
-	Explain how MapReduce processes data. 
-	Define Spark and explain how it processes data.
-	Describe how NLP collets and analyzes text data. 
-	Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
-	Complete an analysis of an Amazon customer review.

## Challenge Overview
Complete an analysis of an Amazon customer review.
Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains more than 1.5 million rows. With more than 40 datasets, this can be quite taxing on the average local computer.


## Challenge Objectives
-	Perform ETL on one of the review datasets.
-	Store your results on an AWS RDS database.
-	Determine if reviews are biased using PySpark or SQL with the appropriate statistical methods.

## Challenge Summary
Instructions
1.) Use the furnished schemata to create tables in our RDS database.
2.) Create a Google Colab Notebook and extract any dataset from the list of review datasets , one into each notebook.
3.) For the notebook, complete the following:
-	Extract the dataset from the S3 bucket and load into a DataFrame.
-	Count the number of records (rows) in the dataset.
-	Transform the dataset to fit the tables in the schema file.
-	Load the DataFrames that correspond to tables into an RDS instance.
4.) Use either PySpark or SQL to analyze the data and determine if the Vine reviews are biased.
-	If you choose to use SQL, use the vine_table from the result of the previous step. Perform your analysis with SQL queries on RDS.
-	If you choose to use PySpark, create a new notebook and perform your analysis there.
-	Consider steps to take to reduce noisy dat

## Colab Link

https://drive.google.com/drive/folders/1CXyC6svcjDCfIrOqC8kx6tNeNxfR0YpU
