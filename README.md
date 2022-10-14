# AWS-SageMaker-Studio-Register-and-Visualize-Dataset

Introduction

In this repo, it is ingested and transformed the customer reviews dataset.Then AWS data stack services such as AWS Glue and Amazon Athena for ingesting and querying
the dataset. Finally Data Wrangler tool is used to analyze the dataset and some visuals are extacted.

Table of Contents
1. Ingest and transform the public dataset
1.1. List the dataset files in the public S3 bucket
Exercise 1
1.2. Copy the data locally to the notebook
1.3. Transform the data
1.4 Write the data to a CSV file
2. Register the public dataset for querying and visualizing
2.1. Register S3 dataset files as a table for querying
Exercise 2
2.2. Create default S3 bucket for Amazon Athena
3. Visualize data
3.1. Preparation for data visualization
3.2. How many reviews per sentiment?
Exercise 3
3.3. Which product categories are highest rated by average sentiment?
3.4. Which product categories have the most reviews?
Exercise 4
3.5. What is the breakdown of sentiments per product category?
3.6. Analyze the distribution of review word counts
