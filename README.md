# Amazon_Vine_Analysis

## Overview of Project
In this project, we are going to analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.

I have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I use Pandas to analyze the data and determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Data
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt


## Results

- How many Vine reviews and non-Vine reviews were there?

total number of Vine reviews:
![Untitled](https://user-images.githubusercontent.com/38533045/138540530-7ca57aca-db83-4e5c-a01f-d981f5c3ef0b.png)


total number of non-Vine reviews:
![Untitled1](https://user-images.githubusercontent.com/38533045/138540542-ed57fdaa-84e2-4084-81b9-9dde070b4a06.png)


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

total number of 5 stars Vine reviews:
![Untitled2](https://user-images.githubusercontent.com/38533045/138540561-2e9b75c1-8fe8-406d-ab16-fc6defbef11a.png)


total number of 5 stars non-Vine reviews:
![Untitled3](https://user-images.githubusercontent.com/38533045/138540578-36eff478-76d5-4805-a3e7-fc12bc5dfa41.png)


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

percentage of 5 stsars Vine reviews:
![Untitled4](https://user-images.githubusercontent.com/38533045/138540602-0f0e9893-6463-4b00-bbab-3c3c8e214c5b.png)


percentage of 5 stars of non-Vine reviews:
![Untitled5](https://user-images.githubusercontent.com/38533045/138540617-e74e7207-a227-4be7-8683-8809199e3674.png)




## Summary

- Is there any positivity bias for reviews in the Vine program?

46.5% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is 53.5%. This describes there is no positivity bias for reviews in the Vine program.

- Additional analysis that we could do with the dataset: 

Additionally we could analyze the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

