# Movie-Recommendation

## Objective:
Our goal of the project is to recommend new movies to users, to dig out what users may like but they did not know before. We aim to build a movie recommendation system by exploring different approaches such as market basket, collaborative filtering, clustering, etc.​
Dataset description:
The data is MovieLens dataset is taken from GroupLens website.
The dataset is spread across multiple csv files. As we can see, one csv file has information about movies like the movie Id, movie title and the genres the movie belong to. Another csv file has information about the user and the ratings the user has given to the movie. 


## Market Basket Analysis
Association rules were found using Apriori algorithm. These association helps us to identify those movies which are frequently watched together by users.


## Collaborative filtering 
Another method we implemented was collaborative filtering. It is a technique that can filter out items that a user might like on the basis of reactions by similar users. It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user. In user-based filtering, the rating of a movie M which hasn't been rated by user U, is calculated by the ratings of other similar users who have rated movie M. For this we predict the rating R, that user U would give to a movie M. If the rating is above a threshold, we recommend the movie to the user. 

## Clustering
Made use of clustering techniques to form clusters of similar users and similar movies. Finally movies were recommended to the users based on the probability of the user liking a particular movie from the list of movies the user has not already watched.
