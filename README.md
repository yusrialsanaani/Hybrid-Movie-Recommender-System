# Hybrid Movie Recommender System - Final Project LHL

## Recommender Systems

Recommender Systems are a type of information filtering system as they improve the quality of search results and provides items that are more relevant to the search item or are related to the search history of the user.
In today’s technology driven world, recommender systems are socially and economically critical for ensuring that individuals can make appropriate choices surrounding the content they engage with on a daily basis.

## Project description
- Developing Knowledge-based, Content-based, Collaborative Recommender system,
and  hybrid movie recommender system that combines user ratings and content of 
the movies  using MovieLens dataset with 25,000095 movie ratings. 
- These Recommender systems will be built using Pandas operations and by fitting some 
scikit-learn/surprise models which use NLP techniques to suggest movies for the users 
based on similar users and for queries specific to genre, user Similarity, movie 
Similarity, rating, popularity, or hybrid query. 

## Recommender System RS Framework

**Dataset:** MovieLens 25M Dataset (https://grouplens.org/datasets/movielens/25m/)

**EDA & Preprocessing:** A comprehensive exploratory data analysis and data preprocessing techniques have been perfmed before injecting the data into recommender system.

**Types of RSs:**
- Content Based RS based on **Movies Genres**
- Collaborative RS based on **Users interactions**
- Hybrid RS that combines **user ratings** and **content of the movies**

**Evaluation Metrics:** Root Mean Squared Error (RMSE) | Mean Absolute Error (MAE) | Hit Rate (HR) | Novelty | Coverage | Diversity

**Software & Tools:** Python version 3.7 | Google Cobal | Jupyter notebook

**Libraries used:** scikit-learn | re | nltk | pandas | numpy | seaborn | plotly | matplot| surprise

**The algorithms used are:** K-nearest neighbour (KNN) | Cosine Similarity | SVD


![image](https://user-images.githubusercontent.com/89004966/171425184-0936e244-6167-4534-9048-78ad6191c3f6.png)


## Content Based Recommender

Content Based RS filter out movies based on movies genres and rating data using KNN and Cosine similarity. The TfiDF and BOW were used to represent the text using vectors.

![image](https://user-images.githubusercontent.com/89004966/171425391-0255a93d-c3c7-4a66-aaa5-da02a02146da.png)


![image](https://user-images.githubusercontent.com/89004966/171425449-e08b33dd-e018-4a8a-9237-1fcf519880d0.png)


## Collaborative Based Recommender
Collaborative RS filter out movies that a user might like based on ratings of similar users.
For example, if user 1 and 2 watched the same A and B movies, user 1 might like movie c as well.
SVD has been used to predict the ratings based on the similarity of users-movies interactions


![image](https://user-images.githubusercontent.com/89004966/171425674-58a57339-34c7-4479-b260-825a7b993276.png)


## Hybrid Recommender

![image](https://user-images.githubusercontent.com/89004966/171425810-3913ab8d-1504-4ade-abc6-064a87342c0f.png)

![image](https://user-images.githubusercontent.com/89004966/171425872-97bf53f1-7195-454f-8336-cccbd757727e.png)


## Evaluation Metrics

![image](https://user-images.githubusercontent.com/89004966/171434443-484c1816-3c0f-4c01-8ff4-3e8a717060bb.png)

![image](https://user-images.githubusercontent.com/89004966/171434484-cefb888f-0b6d-423f-802f-0a96d0f36640.png)

![image](https://user-images.githubusercontent.com/89004966/171434512-919ae9cd-764b-4d55-aa75-693a8e65db1a.png)

![image](https://user-images.githubusercontent.com/89004966/171434541-962b36df-f97e-4c71-9cf3-db972791d62d.png)

![image](https://user-images.githubusercontent.com/89004966/171434565-481b7964-9dd1-45ab-8050-f55982c4cfc1.png)





