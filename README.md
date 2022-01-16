# Cryptocurrencies
Unsupervised Machine Learning

## Project overview

Using Unsupervised Learning to Discover Unknown Patterns
Challenges of Unsupervised Learning

IMPORTANT
    Unsupervised learning isn't the solution for every data analytic challenge.
    Just because supervised learning might not work for one situation doesn't mean
    unsupervised learning will work instead. Understanding the data and what can be
    done with it is an important first step before choosing an algorithm.

Deliverable 1: Preprocessing the Data for PCA
Deliverable 2: Reducing Data Dimensions Using PCA
Deliverable 3: Clustering Cryptocurrencies Using K-means
Deliverable 4: Visualizing Cryptocurrencies Results

Methods in unsupervised ML used are:
- Data Preprocessing
- Clustering and the K-means Algorithm
- Elbow Curve to Find Centroids
- Managing Data Features
- Hierarchical Clustering


## Resources

Primarily use with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. We'll build on this by speeding up the process using principal component analysis (PCA), which employs many different features.


## Analysis and Challenges

### Description of the project:

The Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
>Washigton University of Saint Louis, Bootcamp Data Analytics

The project is analyzed through PCA understanding Herarchical Clustering through the identification of Dendrograms. It was requiered to run the herarchical clustering model and compare results with K-means. The results are as follow in the graphs below:

Elbow Curve
![Elbow Curve](Resources/Elbow%20Curve.png)

3D-Scatter with Clusters
![Scatteplot](Resources/3D-Scatter%20with%20Clusters.png)

Tradable Cryptocurrencies:
![CRYPTO](Resources/Tradable%20Cryptocurrencies.png)

Scatterplot [TotalCoinsMined, TotalCoinSupply]
![Mined](Resources/Scatterplot%20%5BTotalCoinsMined%2C%20TotalCoinSupply%5D.png)

## Summary

In unsupervised learning, there are two key differences from the above approach:

There are no paired inputs and outcomes.
The model uses a whole dataset as input.
Unsupervised learning is used in one of the following two ways:

Transform the data to create an intuitive representation for analysis or to use in another machine learning model; or
Cluster or determine patterns in a grouping of data, rather than to predict a classification.

Refer to the KMeans algorithm from sklearn documentation (https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) to help you cluster the cryptocurrencies using the PCA data.


