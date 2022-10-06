# Amazon_Vine_Analysis
Analysis on Big Data of Amazon's Paid Vine Program Reviews from AWS with implementation of ETL methods with Hadoop and PySpark, Python, PostgreSQL, pgAdmin, and Amazon's S3 and RDS. 

## Resources:
<details>
<summary>Dataset:</summary>

  - [US Apparel Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
</details>

<details>
<summary>Software and IDE:</summary>
  
  - Google Colab 
  - PostgreSQL
    - pgAdmin

</details>

<details>
<summary>Cloud:</summary>

  - Amazon Web Services `AWS`
    - Simple Storage Service `S3`
    - Relational Database Service `RDS`
</details>



## Overview of the analysis of the Vine Program:
The overview of this project was analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. For the analysis we picked the [US Apparel Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We then used PySpark on Google Colab to determine if there is any bias toward favorable reviews from Vine members in the selected dataset.



## Results: 

## Summary: 
