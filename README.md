# Nteflix-Movies-TV-shows-clustering

**Problem Statement**
Netflix is a popular streaming platform that heavily relies on recommendation systems to personalize the viewing experience for its users. Netflix employs a sophisticated recommendation algorithm that analyzes user behavior, preferences, and viewing history to provide personalized movie and TV show recommendations.In this project, we have done clustering of Netflix shows and movies in such a way that shows with similar specification are grouped into same cluster.

**Objective**

The objective is to group Netflix shows into different clusters so that shows with similar specifications lies in one group.

**Data Pipeline**
1. Know Your data: Examine and understand the data
2. Exploratory data analysis: Identifying patterns and draw some conclusion'
3. Data cleaning: Checking duplicated values, addressing null values and outliers.
4. Textual data preprocessing: Removing stopwords, punctuation, converting to lower case and word vectorization.
5. Cluster Implementation: Applying k-means and hierarchial clustering to group shows.
6. Content based recommendation system: It provide 10 recommendation based on your current shows you have watched.

**Conclusion**
- There are 7787 records and 11 columns in the dataset.
- Initially, we have done data cleaning and EDA of the dataset.
- It was found that Netflix produces more movies than TV shows and the total number of shows is increasing rapidly.
- The highest number of shows are found in the United States.
- From 2015, TV shows are also taking prominent place in the Netflix.
- The attributes are chosen for clustering the data: cast, country, genre, director, rating, and description.
- The issue of dimensionality reduction is solved through the use of principal component analysis.
- In K-means clustering, the optimal number of clusters that are formed is 6. The elbow and silhouette method is used to find the perfect number of clusters.
- In agglomerative clustering algorithm, the optimal value of cluster is found to be 7.
- The cosine similarity is used to create a content-based recommender system.
