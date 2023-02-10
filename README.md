# Capstone-Machine-Learning-Unsupervised-Netflix-and-Tv-Show-Clustering-

![image](https://user-images.githubusercontent.com/108147405/218164288-2dd1434a-ddd4-483f-a110-5d61b153abbb.png)

NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING based on unsupervised machine learning algorithms. This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

## Problem Description:

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Our goal here is to make an unsupervised clustering model, which will help in garnering insights on Netflix and how its content is being consumed.

A brief summary of the dataset is given below:
![image](https://user-images.githubusercontent.com/108147405/218164719-9d19e73a-fec2-4362-8fbe-8c517abded44.png)

## Design and Methodology
In this section, we will discuss the framework, extraction and preprocessing features, feature selection, and clustering algorithms.

## Steps Involved

1) Exploratory Data Analysis
2) Data Preparation:

   i. Text Pre-processing a.) Removing Punctuations b.) Removing Stopwords c.) Stemming d.) Creating New Variables for Text Length
   
   ii. Rescaling the data
   
3) Clustering:

i.  Implementing K- Means Clustering

ii. Implementing Hierarchical Clustering

## Conclusion :
After pre-processing the data, I started with EDA to understand the trends and features of the provided dataset. Major findings from EDA are as follows:
•	There is 70% movie content and 30% TV show content in the dataset.

•	The United States account for the majority of the content created on Netflix, numbering 3638 titles. India is the second largest with 972 titles.

•	All the top 10 countries producing highest amount of content have higher proportion of movies than TV shows except Japan, South Korea and Taiwan.

•	Netflix is increasingly focusing on TV Shows now, which is clear from the graph, from 2019 to 2020, there was a decreasing trend of Movies. The TV shows from 2019 to   2020 remains constant.

•	TV-MA, TV-14 and TV-PG are the top content rating to which highest number of contents belongs.

•	Among the top 10 countries with highest content volume, United States and India has highest volume of content appropriate for teens and most other countries have      highest volume of content appropriate for adults.

•	Content onboarding on Netflix started increasing from 2015 and reached to its peak in 2019, there is a drastic downfall in 2021. The downfall can be attributed to  Covid pandemic.

•	International movies is the highest content genre in movies and International TV Shows is the highest one in TV shows.

•	TV shows with one season are highest in number. Findings after applying k- means and Hierarchical clustering:

•	K-means clustering is used to form the clusters of clusters of the content. To find out the optimal value of k, Elbow and Silhouette method was used=6 was  appropriate value and can be visualized after clustering the content using k-means clustering.

•	Hierarchical clustering implementation gives perfect score of silhouettes at 6 clusters, same as visualized using dendrogram.

