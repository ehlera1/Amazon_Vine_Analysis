# Amazon Vine Analysis

## Overview

Working with our partner Jennifer, we will analyze Amazon reviews written by members of the paid Amazon Vine program as we are trying to identify if there is positivity bias for paid review programs. To get started on this project we will review one of 50 datasets for a product category is a part of this program. Our intial analysis will be on the electronics category. 

In this analysis we will: 
 - PySpark to extrct the dataset, transform the data and connect with an Amazon RDS instance that will allow us to query the infomration using postgres. 
 - We will use Google Colaboratory to build our application and connect our tools. 

---


## Results 

In our analysis we wanted to gain a broad picture of of our findings to help better understand if there was bias for Vine (paid) reviews vs. Non-Vine (un-paid) reviews. The table below highlights our overall findings. 

![Vine_Totals](https://user-images.githubusercontent.com/90698381/149670933-8ec969a6-f897-4f9f-ba9a-3870e2d4985b.png)

 - Overall, there were 1,080 Vine reviews and 49,659 non-Vine reviews.
 - Of the 1,080 Vine reviews 454 were 5 stars. 
 - Of the 49,659 non-Vine Reviews 23,034 were 5 stars. 
 - The percentage of Vine reviews that were 5 stars was 42.04%
 - The percentage of non-Vine reviews that were 5 stars was 46.38% 
 
---

## Summary 

In summary, based on our analysis we do not feel there was positivity bias when rating the products on the Vine program. 
We came to this conclusion as the number of 5 star reviews given by non-Vine users was 46.38% of total which was higher than that of the reviews in the Vine program at 42.04%.



### Recomendation 

It would be our recommendation to analyize the specifc products that were in the Vine review program and compare the reviews for those specific products to what was given in the non-Vine reviews.
This may help identify if there was specific bias by product for items within the Vine program vs the entire product category.  
