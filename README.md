# Amazon_Vine_Analysis

## Overview of the analysis

This analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program, who receive products in exchange for a required review. We will use AWS, as well as PySparks and pgAdmin(SQL) to perform the ETL(Extract, Transform, and Load) process. We will connect to an AWS RDS instance, load the transformed data into pgAdmin and use Pyspraks determine if there is any bias toward favorable reviews from Vine members.

## Results 

### How many Vine reviews and non-Vine reviews were there?
* According to the data, there was zero Vine reviews. 
![Screen Shot 2022-05-29 at 10 29 04 PM](https://user-images.githubusercontent.com/98780937/170923124-b662fc88-07d0-4b92-b60b-359d6a50e1bc.png)
![Screen Shot 2022-05-29 at 10 29 16 PM](https://user-images.githubusercontent.com/98780937/170923135-0359740a-7d7d-4169-9187-ca90546ed8c4.png)

* There was a total of 145431 non-Vine reviews, and 1685 non-Vine reviews in our filtered dataset.
![Screen Shot 2022-05-29 at 10 33 01 PM](https://user-images.githubusercontent.com/98780937/170923879-2fd61c8f-37ce-4a44-abaa-a60246363e03.png)
![Screen Shot 2022-05-29 at 10 38 57 PM](https://user-images.githubusercontent.com/98780937/170924311-b5e9ac88-41ff-420b-b68e-6884ade2dcd7.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* According to our dataset, there was a total of 631 five star reviews. There was no Vine reviews, therefore zero reviews were 5 stars and 631 reviews were non-Vine reviews. 
![Screen Shot 2022-05-29 at 10 46 29 PM](https://user-images.githubusercontent.com/98780937/170925408-a3b2492f-2a2f-4e52-9b9e-c9d9512116c9.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* There was 0 percent with 5 star reviews that was from the Amazon Vine program.
![Screen Shot 2022-05-29 at 10 52 05 PM](https://user-images.githubusercontent.com/98780937/170925784-a002bed3-11a8-4caa-adda-c96bcf497303.png)

* There was 37 percent with 5 star reviews that was not from the Amazon Vine program.
![Screen Shot 2022-05-29 at 10 52 13 PM](https://user-images.githubusercontent.com/98780937/170925762-c94abf6e-88ea-4d75-96b8-adad616c6700.png)


## Summary

Unfortuntely, the dataset that was chosen for this analysis did not have any Amazon Vine program reviewers, so there was no positivity bias for reviews in the Vine program. 


