#Amazon_Vine_Analysis

##Overview
###As a data expert at BigMarket we have been assigned a project to analyze
Amazon reviews written by members of the paid Amazon Vine program. In this project
we will have access to approximately 50 datasets. We will pick one of these datasets
and use PySpark to perform the following:

- ETL process to extract the dataset
- Transform the data
- Connect to an AWS RDS instance
- Load the transformed data into pgAdmin
- Leverage PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members

##Results
###The dataset chosen for this challenge was **Pet Products**

*Total Number of Reviews*
- Number of Vine Reviews: 170
![Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/Vine_Reviews.PNG)

- Number of Non-Vine Reviews: 37,840
![Non_Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/Non_Vine_Reviews.PNG)

* Total Number of 5-Star Reviews*
- Number of Vine Reviews: 65
![5-Star_Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/5-Star_Vine_Reviews.PNG)

- Number of Non-Vine Reviews: 20,612
![5-Start_Non_Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/5-Star_Non_Vine_Reviews.PNG)

* Percentage of 5-Star Reviews*
- Percentage of Vine Reviews:38.2%
![Percentage_5-Star_Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/Percentage_5-Star_Vine_Reviews.PNG)

- Percentage of Non-Vine Reviews:54.5%
![Percentage_5-Star_Non_Vine_Reviews](https://github.com/mavalenz/Amazon_Vine_Analysis/blob/main/Resources/Percentage_5-Star_Non_Vine_Reviews.PNG)

##Summary
###In summary, based off our analysis it seems that there isn't a positivity bias for reviews in the Vine program given that the number of reviews were provided by unpaid vine users. Looking at 54% vs 38%. An additional analysis that could be performed with our dataset to support this statement is looking at a statistical distribution calculating the mean, median and mode for both Vine and Non-Vine reviewers.