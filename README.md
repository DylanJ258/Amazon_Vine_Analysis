# Amazon_Vine_Analysis
## Project Overview
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results
* How many Vine reviews and non-Vine reviews were there?

<img width="231" alt="Screen Shot 2022-09-20 at 7 04 54 PM" src="https://user-images.githubusercontent.com/104036750/191386063-5943efaa-6b60-4ab5-9c2c-db1f4125e0ac.png">


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

<img width="271" alt="Screen Shot 2022-09-20 at 7 05 23 PM" src="https://user-images.githubusercontent.com/104036750/191386074-877d3f4e-9a8a-4927-a60a-45f38cf1683a.png">



* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<img width="266" alt="Screen Shot 2022-09-20 at 7 06 40 PM" src="https://user-images.githubusercontent.com/104036750/191386081-717ef236-e622-4663-b8c5-c5c3e49ccee6.png">

## Summary
* Overall, utilizing the Vine subscription doesn't seem to make a too much of a difference in review ratings for Sport products. 
Around 42% of the paid reviews were 5 star, which around 53% of the unpaid reviews were 5 stars.
* Analyzing the length of reviews for paid and unpaid users could be beneficial. Longer reviews could be more helpful for customers trying to decide if they want to purchase a product.
