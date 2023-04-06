# Amazon_Vine_Analysis

## Overview of the analysis

Explain the purpose of this analysis.
In this project, we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We picked Gift Cards datasets. We used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. And then used PySpark again to determine if there is any bias toward favorable reviews from Vine members in our dataset.

## Resources
Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL, pgAdmin, AWS

## Results
Using bulleted lists and images of DataFrames as support, address the following questions:
There are 149086 total reivews
There are 129709 5-star reviews
There are total 0 vine (vine = Y) reviews
There are 0,Five-star vine (vine = Y) reviews
There are 0.0 % 5-star vine (vine = Y) reviews
There are total 149086 non-vine (vine = N) reviews
There are 129709 5-star non-vine (vine = N) reviews
There are 87.0 % 5-star non-vine (vine = N) reviews

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.



The written analysis has the following:

Overview of the analysis of the Vine program:

The purpose of this analysis is well defined (3 pt)
Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)
Summary:
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
