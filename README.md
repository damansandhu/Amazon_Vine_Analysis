# Amazon_Vine_Analysis
## Analysis
### Overview
This project analyzes Amazon reviews to see if the Amazon Vine program reviews show a bias towards higher ratings from the Amazon Vine users.
PySpark was used to perform the ETL process to extract, transform, and connect the data to an AWS RDS instance. The data was then loaded from an AWS RDS instance to pgAdmin where it was used to calculate various metrics. Data from Amazon Digital Video Game reviews was used for this analysis.
### Results
Total Vine Reviews
![total_paid_reviews](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/total_paid_reviews.png)


Total Non-Vine Reviews
![total_unpaid_reviews](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/total_unpaid_reviews.png)


5 Star Vine Reviews
![5_star_paid_reviews](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/5_star_paid_reviews.png)


5 Star Non-Vine Reviews
![5_star_unpaid_reviews](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/5_star_unpaid_reviews.png)

5 Star Vine Reviews Percentage
![5_star_paid_precentage](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/5_star_paid_percentage.png)

5 Star Non-Vine Reviews Percentage
![5_star_unpaid_precentage](https://raw.githubusercontent.com/damansandhu/Amazon_Vine_Analysis/main/images/5_star_unpaid_percentage.png)

### Summary
51% of the reviews in the Vine program were 5 stars reviews, while only 39% of the Non-Vine unpaid reviews were 5 Star. This provides evidence for a bias towards positive reviews from users in the Vine program.
Furthermore, we could find the mean, median and mode of the star rating for the Vine and non-Vine reviews to see if there is greater variance in the ratings between Vine and Non-Vine member's reviews.
