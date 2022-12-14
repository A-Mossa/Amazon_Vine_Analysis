# Amazon_Vine_Analysis
## Overview of the project

This project analyzes Amazon Vine program that permits vendors and store operators to post a paid review of their product. Purpose of this project is analyzing the members reviews' bias when incentivized by the platform.
PySpark was used for this analysis to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
The Dataset of choice was (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)

## Results

- How many Vine reviews and non-Vine reviews were there?
  - Paid Vine reviews yielded a total of 94 reviews.
  - Reviews unpaid by vine were a total of 40471 reviews.
  - Total number of reviews were 40565.
  
![Number of Reviews](https://github.com/A-Mossa/Amazon_Vine_Analysis/blob/main/Imgs/number%20of%20reviews.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Number of paid review that were 5-stars was 48.
  - Number of unpaid review that were 5-stars was 15663.

![Number of 5-stars Reviews](https://github.com/A-Mossa/Amazon_Vine_Analysis/blob/main/Imgs/5star%20percent.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - percentage of paid vine reviews that were 5-stars was 51.06%
  - percentage of unpaid vine reviews that were 5-stars was 38.7%

![percent of 5-stars Reviews](https://github.com/A-Mossa/Amazon_Vine_Analysis/blob/main/Imgs/5star%20percent.png)

## Summary

A significant 51% of the reviews in the paid Vine program were 5 stars reviews, on the other hand the percentage of 5-star non-Vine reviews is around 38.6%. This indicates that incentivizing reviews impacts bias.

Regarding additional analysis, the team first would like to apply the same process over a variety of dataset for different products to verify results.
Also, comparing the analysis results with different datasets for companies offering similar service to Vine to verify that incentivizing reviewers encourages bias.
