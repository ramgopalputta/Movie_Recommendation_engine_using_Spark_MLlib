# WHAT IS MOVIE RECOMMENDATION ENGINE ?
* This tool makes personalized movie recommendations tailor for the user.
* Movie is recommended based on his/her past viewed movies and also based on other users with similar interest.
* This engine is build using Spark MLlib tool.

# SPARK MLLIB
* MLlib is the spark’s scalable machine learning library consisting of common Machine learning algorithms.
* In this project, ‘Collaborative Filtering’ technique is implemented for creating recommendations.

# COLLABORATIVE FILTERING:
* Collaborative filtering is a type of machine learning algorithm that recommends items to users based on the preferences of other users with similar tastes.
* Also known as Social filtering, this technique aims to fill the missing entries of a user-item association matrix (user-movie rating matrix) in which users and movies are described by a set of latent factors.
* To implement this technique in this project, Alternate Least Square (ALS) algorithm is used to learn these factors.

# MOVIE-USER RATING MATRIX FACTORIZATION:
* It is a technique used in movie recommendation engines to decompose the user-movie rating matrix into two lower-dimensional matrices, one for users and one for movies. The resulting matrices represent latent features of users and movies, respectively. These latent features can be used to predict user ratings for unwatched movies, and to recommend movies to users that they are likely to enjoy.

![image](https://github.com/ramgopalputta/Movie_Recommendation_engine_using_Spark_MLlib/assets/114395443/5f3b1bec-116a-4936-b916-3a7dd89190a5)

This technique effectively handles data sparsity, i.e., the fact that most users have only rated a small fraction of the movies available.

# Alternate Least Square (ALS) algorithm
* ALS is an iterative algorithm where in each iteration, the algorithm fixes one factor matrix and solves for other. This process continues till it converges.
(This alternation between which matrix to optimize is where the "alternating" in the name comes from.)

# HOW COLLABORATIVE FILTERING WORKS:

![image](https://user-images.githubusercontent.com/114395443/227746181-a48801aa-20e8-4fd9-bd08-959d7bb44079.png)

From the above User rating table, the interests of USER 3 seems similatr to USER 1. Hence, MOVIE 5 is recommended to USER 3.

# CHALLENGES FACED BY COLLABORATIVE FILTERING:

![image](https://user-images.githubusercontent.com/114395443/227746278-fa8d539a-f08c-4b1e-a718-146d98f1659e.png)





References:
[https://www.youtube.com/watch?v=d5u8JJRmALY](https://aws.amazon.com/blogs/machine-learning/build-a-movie-recommender-with-factorization-machines-on-amazon-sagemaker/)https://aws.amazon.com/blogs/machine-learning/build-a-movie-recommender-with-factorization-machines-on-amazon-sagemaker/
https://bard.google.com/

