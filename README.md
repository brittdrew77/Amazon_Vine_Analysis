# Amazon_Vine_Analysis
## Overview of the Analysis
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine Program. I used PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used Pyspark to determine if there is any bias in reviews from members of the Vine Program. 

## Results

<img width="381" alt="Screen Shot 2022-08-30 at 12 01 43 AM" src="https://user-images.githubusercontent.com/105089651/187346785-d03e2f88-76bc-4854-8bbc-94c1fa7b565b.png">

* There were 613 Vine reviews and 64,968 non-Vine reviews.

<img width="679" alt="Screen Shot 2022-08-30 at 12 02 43 AM" src="https://user-images.githubusercontent.com/105089651/187346788-eb509239-c3d3-4c6d-b8cf-01f9365f84e0.png">

* There were 222 paid five star reviews and 30,543 unpaid five star reviews. 

<img width="593" alt="Screen Shot 2022-08-30 at 12 03 18 AM" src="https://user-images.githubusercontent.com/105089651/187346794-0a1c821a-5df1-49ac-9752-3efd11ce9e5b.png">

* Of the total Vine reviews, approximately 36.22% were five stars. For the total non-Vine reviews, about 47.01% were five stars. 

## Summary
According to this analysis, there does not appear to be any positivity bias for reviews in the Vine program. This is apparent due to the fact that there is a higher percentage of five star unpaid reviews, compared to five star paid reviews. There is also a much higher number of unpaid five star reviews than paid five star reviews. For further analysis of bias in the Vine program, I would look at length of the review_body column compared to star_rating between the paid and unpaid. This could reveal which program provides more feedback and which star rating receive the longest reviews. It could answer questions regarding if the Vine program customers offer more constructive feedback compared to the unpaid program. 
