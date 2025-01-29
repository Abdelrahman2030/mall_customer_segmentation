# Mall customer segmentation

## Problem Statement
We want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

By the end of this case study , you would be able to answer below questions.
1. How to achieve customer segmentation using machine learning algorithm (KMeans Clustering) in Python in simplest way.
2. Who are your target customers with whom you can start marketing strategy [easy to converse]
3. How the marketing strategy works in real world

## About the data
**Context**   
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.   
[Data Link on Kaggle ](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## Approach

1. Preprocessing 
    - Data cleaning and preparation.

2. Applying K-Means Clustering
    - Segmentation into 4 clusters.

3. Cluster Analysis 
    - Identifying patterns and characteristics.


## Cluster Insights
- Clusters have a strong relation with `annual income` **(Clsuter(2): Is mainly with lower income, Cluster(0): Is mainly with medium income,**    
**clusters(1, 3): Both has high income)**
- Clusters has a strong relation with `spending score` **(Cluster(2): Varies in score, Cluster(0): Has medium score, Cluster(1): Has high score,**   
**Cluster(3): Has low score)**
- Clusters has a good relation with `age` as **(Clsuer(1): Has an age range from 25 to 50, but other clusters vary in age)**

## Characteristics of group 1 that has the highest spending score
- **`Age:`**   
    - Ranges from 27 to 40
    - Mean is 32
    - Median is 32
    - Normaly distriputed

- **`Annual Income (unit in 1000 USD):`**   
    - Ranges from 69 - 137
    - Mean is 86
    - Median is 79
    - Slight right skewd