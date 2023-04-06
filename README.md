# Amazon_Vine_Analysis

## Overview of the analysis
Our objective in this project is to take an extensive look at the Vine users reviews. We have access to different datasets from this [link](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt "link"). The product we chose to take deeper dive is personal care appliences. We used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. And then used PySpark again to determine if there is any bias toward favorable reviews from Vine members in our dataset.


## Results
- In this data set, there were  3  Vine reviews and  3094  non-Vine reviews.

![Total Vine reviews](Images/total_vine.PNG)
![Total non-Vine reviews](Images/total_unpaid.PNG)

There were  Vine reviews that were 5 stars and  1704  non-Vine reviews were 5 stars.
![5 star Vine reviews](Images/5_star_vine.PNG)
![5 star non-Vine reviews](Images/5_star_unpaid.PNG)

66.6 percentage of Vine reviews were 5 stars and 55 percentage of non-Vine reviews were 5 stars.
![Percentage of 5stars Vine reviews](Images/per_5_star_vine.PNG)
![Percentage of 5stars non-Vine reviews](Images/per_5_star_unpaid.PNG)

# Summary: 
66.6% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 55%. This describes a positivity bias for reviews in the Vine program. Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

