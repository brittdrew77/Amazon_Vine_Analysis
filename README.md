# Amazon_Vine_Analysis
## Overview of the Analysis
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine Program. I used PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used Pyspark to determine if there is any bias in reviews from members of the Vine Program. 

## Results


* There were 613 Vine reviews and 64,968 non-Vine reviews.

* There were 222 paid five star reviews and 30,543 unpaid five star reviews. 

* Of the total Vine reviews, approximately 36.22% were five stars. For the total non-Vine reviews, about 47.01% were five stars. 


## Summary
According to this analysis, there does not appear to be any positivity bias for reviews in the Vine program. 
