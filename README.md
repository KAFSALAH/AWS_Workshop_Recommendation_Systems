## Amazon training for recommendation systems 

In this repository, we built four recommendation models based on users’ interactions (users’ ratings 1-5) for [Amazon products](https://github.com/KAFSALAH/AWS_Workshop_Recommendation_Systems/blob/main/Amazon_Products_Recommendation.ipynb) :shirt: :handbag: and [Yelp Restaurants](https://github.com/KAFSALAH/AWS_Workshop_Recommendation_Systems/blob/main/Yelp_Restaurants_Recommendation.ipynb) :lobster: :doughnut:.

Generally, we can categorize recommendations into two major categories, i.e., personalized or non-personalized.

## Non-Personalized approach 

It is the simplest approach as it is based on the popularity of items. 

Model 1 - Rank-Based Recommendation System [Popularity-based]

To build the rank-based recommendation system, we take the average of all the ratings provided to each item and then rank them based on their average rating. It is usually used to avoid cold-starts. 

## Personalized approaches  
Model 2: Building User-User Collaborative Filtering Model [KNN - Similarity-based]

Model 3: Building Item-Item Collaborative Filtering Model [KNN - Similarity-based]

Model 4: Building Model Based Collaborative Filtering Recommendation System - Matrix Factorization [NMF - Model-based]

Credit: All thanks to AWS, and Mr [Surendran Selvaraju](https://www.linkedin.com/in/surendr/).
