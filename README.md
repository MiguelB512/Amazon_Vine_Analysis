# Amazon_Vine_Analysis


## Overview
This project focuses on analyzing customer reviews for amazon products and seeing if there was any bias when customers were paid to review a product vs when the review was done organically. Amazon Vine is program that pays customers to review certain products they recieve from Amazon. This may lead to a bias in positive reviews, which is what we will be looking at today

## Results

### Vine Reviews 
First we will look at the overview for the Vine Reviews dataframe, shown below: <br><br>
![image](https://user-images.githubusercontent.com/60283799/188042867-26dc6b61-c68d-4d31-b656-5c5ea46862b1.png)

We can see the three main factors:
- The total number of reviews (1032)
- The number of 5 star reviews (440)
- The percentage of 5 star reviews compared to the total number of reviews (42.64 %)

This is a solid outcome, it shows that there is a good chunk of total reviews to look at and that about half of them are 5 star reviews when it comes to paid, Vine reviews

<hr>

### Non-Vine Reviews
Now we can take a look at the non-paid reviews: <br><br>
![image](https://user-images.githubusercontent.com/60283799/188042843-bc6eaba3-2a99-4899-905c-8ed9787ef164.png)

The stats for then non-vine reviews are as follows:
- The total number of reviews (46776)
- The number of 5 star reviews (21755)
- The percentage of 5 star reviews compared to the total number of reviews (46.51 %)

## Summary
When it comes to this analysis, it seems that there is no influence on customer reviews based on wheather they are paid for said review or not. The percentage of 5 star reviews were very similar when it comes to paid vs non-paid reviews. Customers seem to still be giving their honest opinion on the product regardless of the compensation. This is good news, it means that the reviews are trustworthy and valid.

A few changes i would make would be to look at other datasets to assure it was the same outcome across all product types, i would attempt to add a column for "time used" that takes into account the amount of time that a customer used the product before submitting their review to see weather they were just sending in a quick review to get it over with or if they actually used the produxt to its full extent and gave an honest review. 

