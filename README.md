# Amazon_Vine_Analysis

Overview of the analysis: 
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Main purpose of this analysis is then to determine if there is any bias toward favorable reviews from Vine members in our dataset.

Procedure:
We haveaccess to approximately 50 datasets,each one containing reviews of a specific product, from clothing apparel to wireless products. We picked music dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we used PySpark, and Pandas to determine if there is any bias toward favorable reviews from Vine members in our dataset.

Results:
Number of Vine reviews and non-Vine reviews:

![vine reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/total_vine_reviews.png)

![non vine reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/total_non_vine_reviews.png)

How many Vine reviews were 5 stars? 

![vine 5star reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/5star_vine_reviews.png)

How many non-Vine reviews were 5 stars?

![non vine 5star reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/5star_non_vine_reviews.png)

What percentage of Vine reviews were 5 stars? 

![vine reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/percentage_5star_vine_reviews.png)

What percentage of non-Vine reviews were 5 stars?

![vine reviews](https://github.com/RGK73/Amazon_Vine_Analysis/blob/main/Images/percentage_5star_non_vine_reviews.png)

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
