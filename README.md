# Subway's Yelp-Reviews Analysis and Data Visualization

This project aimed to assist Subway CEO John Chidsey in addressing the Subway Reviews Problem by analyzing Yelp's review data and creating informative visuals tailored to address the concerns of each level of management. The project was conducted as part of the Cornell University MSBA BANA 5440 Statistical Programming Course.

## Table of Contents
1. [Demonstrated Skills](#demonstrated-skills)
2. [Background](#Background)
3. [Results](#Results)


## Demonstrated Skills
* Data Cleaning using Pandas
* Data Visualizaiton using Matplotlib


## Background

Subway CEO John Chidsey received a report from his field officer that customers are unhappy with one of its stores in Milford, CT, where Subway is headquartered. Upon checking the online reviews for this store, he finds that the average rating received by the store is 3.2/5. John is concerned that if a store next to the headquarters is at 3.2/5, stores farther away might be performing even more poorly. 
John calls for an urgent meeting of the Head of Customer Service, the Head of Store Operations, the Head of Social Media, and the Chief Data Scientist (your boss). He expresses his concern and urges the team to take measures to improve the average ratings received across all stores in the U.S. to 4.5/5.
His team tells him not to worry by making the following statements: 

* Head of Customer Service: “Our ratings are gradually improving, and we will soon reach 4.5/5.”
* Head of Store Operations: “Sandwiches are a tricky business. All sandwich chains suffer from poor customer ratings.”
* Head of Social Media: “The goal of 4.5/5 is unreasonable for national chains like us. Only small, local, and boutique restaurants can achieve such high ratings.”
*	Chief Data Scientist: “It is well known that customers make the effort to give a rating only when they are either extremely angry or absolutely delighted with the     service. So online ratings are not reliable.”



## Results

**1. Part A: Does the data support the statement made by the Head of Customer Service?
     Part B: Is this statement valid across all states? 


![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig1_Rating_Trends.png)

In summary, the data does not support the statement made by the Head of Customer Service that Subway's average rating has been consistently increasing since 2006. While there is no clear increasing or decreasing trend from 2006 to 2014 due to a small number of ratings, the average rating remains between 2.0 to 3.0 as the number of ratings increases.

![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig2_Nationalwide_Rating_Trends.png)

Furthermore, a plot was generated to compare the average rating and number of ratings in four states (FL, CA, PA, and IL) from 2006 to 2022. From 2012 to 2020, the average rating across these states ranged from 1.5 to 3.5, and there is a slightly decreasing trend in rating from 2015 to 2021. However, PA and FL ratings show a trend of increasing in 2021 and onwards. While the data is representative and meaningful, the analysis suggests that Subway's average rating is not consistently high across all states.


**2. Part A: Are sandwiches the only tricky business?

![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig3_Competitor_Ratings.png)

In summary, a time series plot was created to compare the mean and standard deviation of reviews received by Subway with two of its competitors, Arby's and Jimmy John's. The data supports the statement made by the Head of Store Operations, as all three chains experienced a drop in ratings to around 2.0-3.0 when the number of ratings increased from 2014 to 2022.

This suggests that sandwiches are not the only tricky business, as even traditional fast-food chains like Arby's struggle to maintain high ratings. While Subway is the largest chain in the sandwich industry, its competitors are similar in size and also serve other traditional fast-food meals. Obtaining a higher rating for major fast-food chains generally requires significant effort.

**3. Part A: Does the data support the statement made by the Head of Social Media? 
     Part B: Is it true that average rating decreases as the size of restaurant increases?
  
  ![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig3_Local_National_Rating_comparison.png)
   
   In summary, for Part A, the data supports the statement made by the Head of Social Media that local stores tend to have a higher average rating than national stores. From 2005 to 2022, there are rarely any national stores that come close to the 4.5 rating, while local stores have an average rating of 4/5 throughout the years.

![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig4_Size_Ratings.png)

For Part B, the plot shows a clear trend of a decrease in ratings as the size of the restaurant expands. Although there are some spikes in ratings at certain points, overall, the data supports the idea that the average rating decreases as the size of the restaurant increases.



**4. Part A Does the data support the statement made by the Chief Data Scientist? 
     Part B: Is the statement true across all years from 2018 to 2021? 
     
 ![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig5_Ratings_Mesurement.png)
 
     
Part A: The data supports the statement made by the Chief Data Scientist that customers tend to leave a rating when they are extremely unsatisfied or happy with the shops, but does not support the claim that online ratings are unreliable.
Part B: The statement is true across all years from 2018 to 2021, as shown by the consistently higher number of one and five-star ratings compared to two, three, and four-star ratings.

![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig5_Ratings_Mesurement.png)

Based on the insights generated from questions 1 through 4, the recommendation would be to improve Subway's average rating to a 3.5-4/5 by addressing the prevalent issues that drive customers to leave one and two-star ratings. This could be achieved by analyzing the feedback from these customers, identifying and fixing the root causes of their dissatisfaction. While the target of 4.5/5 may be too high for a national fast-food chain like Subway, an improvement in ratings is possible and necessary to address customer dissatisfaction and improve overall business performance.





