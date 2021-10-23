# Amazon_Vine_Analysis

## Overview of Project
In this project, we are going to analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.

I have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I use Pandas to analyze the data and determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Data
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt


## Results

- How many Vine reviews and non-Vine reviews were there?
total number of Vine reviews:


total number of non-Vine reviews:


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
total number of 5 stars Vine reviews:


total number of 5 stars non-Vine reviews:


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
percentage of 5 stsars Vine reviews:


percentage of 5 stars of non-Vine reviews:




## Summary
Is there any positivity bias for reviews in the Vine program?

Additional analysis that we could do with the dataset: 

