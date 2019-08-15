# Collaborative filtering ecommender Systems
![1_aSq9viZGEYiWwL9uJ3Recw](https://user-images.githubusercontent.com/46146748/63115930-5f6c1900-bf66-11e9-894f-ecde5ec531b0.png)

## Goal of the analysis
In this unit, I work towards creating a recommender system using an item-based collaborative filter and cosine similarity in R. It will suggest which unit student should tackle next.

## Packages Requried
```
install.packages("lsa") 
install.packages("tidyr") 
```

## Procedures
1. Upload both the interest and difficulty csv files
2. Convert both data frames to matrices
3. Generate a user-based similarity matrix based on cosine similarity using the ratings the class gave each unit
4. Find out who have the most similar interests with me in class
5. Create a unit-based similarity matrix for difficulty and provide suggestions on which following unit a student is going to do based on the similarity of difficulty to another unit (e.g: "prediction")
6. Create a composite measure (e.g.: PCA) from interest and difficulty, then construct a similarity matrix using this measure
7. Generate a suggestion for a student who has just completed the "prediction" unit

## Background
Collaborative filtering is the process of filtering or evaluating items through the opinions of other people (collaboration).It suggest content to a given user by developing a truly personalized view of that item using the opinions most appropriate for a given user or group of users “neighbors” (filtering). They are very commonly used in scenarios where there is incomplete information about a user's preferences such as Netflix suggestions or product recommendations on Amazon. It predicts what information users are likely to want to see, enabling providers to select subsets of information to display in the limited screen space and enabling the web to adapt to each individual users' needs.

In education industry, an idealized recommender system provides a limited number of suggested metrics or new content based on the learner's past behavior and the patterns of all other learners in the sample. Recommender systems may provide behavioral cues, new content, insights or suggested behavioral changes based on a comparison of the learner to all other learners in the system.


## Definitions and concepts
* User- based collaborative filtering methods: it generats predictions for users based on ratings from similar users. If a user n is similar to a user u, we say that n is a neighbor of u. User-based algorithms generate a prediction for an item i by analyzing ratings for i from users in neighborhood. 

* Item-based collaborative filtering methods: while user-based algorithms generate predictions based on similarities be-tween users, item-based algorithms generate predictions based on similarities between items. 
