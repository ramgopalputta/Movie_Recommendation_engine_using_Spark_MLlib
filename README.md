# WHAT IS MOVIE RECOMMENDATION ENGINE ?
• This tool makes personalized movie recommendations tailor for the user.

• Movie is recommended based on his/her past viewed movies and also based on 
other users with similar interest.

• This engine is build using Spark MLlib tool.

# SPARK MLLIB
• MLlib is the spark’s scalable machine learning library consisting of common 
Machine learning algorithms.

• In this project, ‘Collaborative Filtering’ technique is implemented for creating 
recommendations.

# COLLABORATIVE FILTERING:
* Collaborative filtering is a type of machine learning algorithm that recommends items to users based on the preferences of other users with similar tastes.
• Also known as Social filtering, this technique aims to fill the missing entries of a
user-item association matrix (user-movie rating matrix) in which users and
products (movies) are described by a set of latent factors.

• To implement this technique in this project, Alternate Least Square (ALS)
algorithm is used to learn these factors.

• ALS is an iterative algorithm where in each iteration, the algorithm fixes one
factor matrix and solves for other. This process continues till it converges.
(This alternation between which matrix to optimize is where the "alternating" in
the name comes from.)

# HOW COLLABORATIVE FILTERING WORKS:

![image](https://user-images.githubusercontent.com/114395443/227746181-a48801aa-20e8-4fd9-bd08-959d7bb44079.png)

From the above User rating table, the interests of USER 3 seems similatr to USER 1. Hence, MOVIE 5 is recommended to USER 3.

# CHALLENGES FACED BY COLLABORATIVE FILTERING:

![image](https://user-images.githubusercontent.com/114395443/227746278-fa8d539a-f08c-4b1e-a718-146d98f1659e.png)

