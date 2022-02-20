# Amazon_Vine_Analysis

## Overview
The objective of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program and by members outside of the program. The dataset used was based on toys. I used PySpark to the perform the ETL process to extract the dataset, transform the data, and connect to an AWS Relational Database Service instance, and load the data into PgAdmin. Next, I used Pandas to determine if there is any bias toward favorable reviews from Vine members in the dataset.


## Results
<img width="312" alt="Screen Shot 2022-02-20 at 2 59 33 PM" src="https://user-images.githubusercontent.com/91519293/154864218-fb9ffb11-cfc2-4454-b8f7-272b92bf9e5a.png">

- How many Vine reviews and non-Vine reviews were there?
  - There were 1,266 Vine reviews and 62,028 non-Vine reviews.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Of the 1,266 Vine reviews, 432 reviews awarded 5 stars to the products. 29,982 Non-Vine reviews were 5 stars.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - The percentage of Vine reviews that were 5 stars was 34.12% whereas it was 48.34% for non-Vine reviews that were 5 stars.

## Summary
Based on my breakdown table of the results, I do not believe there is any positivity bias for reviews part of the Vine program. A larger percentage of 5 star reviews would be an indication of some sense of positivity bias, but in this case non-Vine reviews gave out more 5 star reviews. In addition, the proportion is Vine reviews to non-Vine reviews is highly unproportional. Another analysis that could be performed is looking at 4 Star reviews and above for both Vine and non-Vine reviews, for 4 Stars is still highly positive and it would include 4.5 and 5 Star ratings as well, which would provide a more inclusive picture to judge bias from.
