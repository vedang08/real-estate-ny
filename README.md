# Unsupervised Learning clustering techniques for forecasting real estate prices in New York

Real Estate is usually categorized into smaller regional pockets where the location determines the value of the asset. In a more machine learning sense, we could consider these pockets to be clusters where each cluster can be considered to represent a similar type of real estate opportunity. Such type of analysis could be useful to make real estate investment decisions. 

## Goal
The goal of this project is to carry out analysis on the data for all the counties in New York state and use unsupervised machine learning and optimization techniques to divide the counties into optimal number of groups allowing for further analysis in such a way that can help guide financial decision making.

## Data
The real estate data has been provided by Redfin and can be accessed [here](https://www.redfin.com/news/data-center/)

## Work
The execution of multivariate time series forecasting using clustering methods based on unsupervised learning techniques was possible with implementations provided by [tslearn](https://tslearn.readthedocs.io/en/stable/index.html). Utilizing Dynamic Time Warping(DTW) implementation, optimization and visualization was carried out for K-means with Euclidean metrics and DTW-Barycenter Averaging(DBA) K-means with the results being:
 - K-means Euclidean
     - **Univariate:-** Inertia = 18.728486338326018, Clusters = 7
     - **Multivariate:-** Inertia = 205.83835261826746, Clusters = 9
 - DBA-K-means
     - **Univariate:-** Inertia = 7.818229387121636, Clusters = 6
     - **Multivariate:-** Inertia = 213.33150461494134, Clusters = 7

## Author
**Name:** Vedang Naik

**Date:** 17/03/2024

## Note
The notebook contains maps which cannot be viewed on GitHub, to view the visualization of clusters, download the notebook or check it out on my [Kaggle](https://www.kaggle.com/code/vedangnaik/real-estate-ny/notebook)
