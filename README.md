# Collaborative filtering ecommender Systems

As the amount of educational data available to us has grown, the task of organizing and making use of it has become more daunting. [Duval (2011)](dl.acm.org/citation.cfm?id=2090118) saw recommender systems as a way to deal with the "paradox of choice", the dilemma of determining what information to feed back to learners about their learning. 

Collaborative filtering is the process of filtering or evaluating items through the opinions of other people (collaboration).It suggest content to a given user by developing a truly personalized view of that item using the opinions most appropriate for a given user or group of users (“neighbors”) (filtering). They are very commonly used in scenarios where there is incomplete information about a user's preferences such as Netflix suggestions or product recommendations on Amazon. It predicts what information users are likely to want to see, enabling providers to select subsets of information to display in the limited screen space and enabling the web to adapt to each individual users’ needs.

In education industry, an idealized recommender system provides a limited number of suggested metrics or new content based on the learner's past behavior and the patterns of all other learners in the sample. Recommender systems may provide behavioral cues, new content, insights or suggested behavioral changes based on a comparison of the learner to all other learners in the system.


## Definitions and concepts
User- based collaborative filtering methods: it generats predictions for users based on ratings from similar users. If a user n is similar to a user u, we say that n is a neighbor of u. User-based algorithms generate a prediction for an item i by analyzing ratings for i from users in u’s neighborhood. 

Item-based collaborative filtering methods: While user-based algorithms generate predictions based on similarities be-tween users, item-based algorithms generate predictions based on similarities between items. 


## Goal of the analysis

In this unit, I work towards creating a recommender system using an item-based collaborative filter and cosine similarity in R. It will suggest which unit student should tackle next.


### Related Readings

[Drachsler, H., Verbert, K., Santos, O. C., & Manouselis, N. (2015). Panorama of recommender systems to support learning. In *Recommender Systems Handbook* (pp. 421-451). Springer: New York, NY.](https://lirias.kuleuven.be/bitstream/123456789/476545/1/TEL_RecSys.pdf)

[Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In *The Adaptive Web* (pp. 291-324). Springer: Berlin, Heidelberg.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)

[Fazeli, S., Drachsler, H. & Sloep, P. (2017). Applying recommender systems for learning analytics: A tutorial. In *The Handbook of Learning Analytics* (pp. 235-240). SOLAR: Vancouver, BC](https://solaresearch.org/hla-17/hla17-chapter20/) 

[Principal Compononent Analysis - Visually Explained](http://setosa.io/ev/principal-component-analysis/)


### Related Videos

[Leskovec, J., Rajaraman, A. & Ullman, J. (2017). Recommender systems: Collaborative filtering. In *Mining of Massive Data Sets*. Coursera: Stanford, CA](https://www.youtube.com/watch?v=h9gpufJFF-0)

Brinton, C. & Chiang, M. (2013). Cosine similarity. In *Networks Illustrated: Principals without Calculus*  
[Part A](https://www.youtube.com/watch?v=C-JauEnlSlM)  
[Part B](https://www.youtube.com/watch?v=-gz1qdsM0tk)  


