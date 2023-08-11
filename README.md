# Scraping-And-Clustering-Football-Data
Showcasing a web scraping workflow using python and identifying how to pick the optimal k value for KMeans clustering.

The goal of the project is to pick the best k value using a silhouette analysis as well as a wcss(elbow method) analysis to identify which values for k will create meaningful and informative clusters. 
To achieve these goals, I took the following steps:

1. Scrape stats stats data.
2. Clean the stats data.
3. Perform Kmeans clustering on data. 


## Requirements
* selenium
* requests
* BeautifulSoup
* numpy
* pandas
* scikit-learn
