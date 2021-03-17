# Amazon_Vine_Analysis

## Overview 

The purpose of this analysis is to analyze the amazon reviews written by members of the paid Amazon Vine program. The data is categorized into paid and unpaid reviews. The data set chosen was Amazon Toys reviews. The dataset comprises of the following columns :

    * Marketplace
    * customer_id
    * review_id
    * product_id
    * product_parent
    * product_title
    * product_category
    * star_rating
    * helpful_votes
    * total_votes
    * vine
    * verified_purchase
    * review_headline
    * review_body
    * review_date

## Results

1) Total number of reviews where the helpful_votes/total_votes is greater than 50% =  63,294
2) Total Number of vine reviews = 1,266
3) Total Number of non vine reviews = 62,028
4) Number of 5 star vine reviewers = 432
5) Number of 5 star non vine reviews = 29,982
6) % of 5 star vine reviewers = 34.12%
7) % of 5 star non vine reviewers = 48.34%

Screenshots of analysis :

![Number of records](https://github.com/surchand30/Amazon_Vine_Analysis/blob/main/images/Number%20of%20records.PNG)

![5 star rating analysis](https://github.com/surchand30/Amazon_Vine_Analysis/blob/main/images/5%20Star%20reviews%20analysis.PNG)

## Summary

Based on the results of the analysis, a bias is strongly evident in the dataset we analyzed. Less than 20% of the total votes are from vine reviews.There is a huge difference between the number of vine reviews and number of non vine reviews.I would be interested in knowing what percentage of the 5 star ratings from both vine and non vine reviews resulted in a verified purchase.
