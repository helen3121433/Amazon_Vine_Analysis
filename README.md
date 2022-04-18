# Amazon_Vine_Analysis

## Overview
- The purpose of this analysis is analyzing Amazon reviews written by members of the paid Amazon Vine program vs reviews written by non-vine program members.

- Sources used: 
    - https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz
    - Amazon AWS - RDS, S3
    - pgAdmin 4 - Postgres SQL
    - Google Colab Notebook - PySpark

## Results
- Musical Instruments dataset was in this project. We filter out and only keep dataset that has total_votes greater than 20 and has helful_votes over 50%.
    - Total number of Vine reviews was 60
    - Total number of 5-stars vine reviews was 34
    - Percentage of 5-star vine reivews was roughly 56.67%

    - Total number of non-Vine reviews was 14477
    - Total number of 5-stars non-vine reviews was 8212
    - Percentage of 5-star non-vine reivews was roughly 56.72%

## Summary
- Looks like vine program does not have huge effect on Musical Instruments products. The percentage of 5 star reivew were almost the same. Additional, not many only 60 reviews from vine members. However, we should make couple more comparsion to support the statement, such as average of star reviews, number of verfied_purchase, number of reivew by each review date, etc. Additional, we should also run couple more other product dataset to compare the results. 


    