# Unsupervised-Capstone-Project
Netflix Movies and TV Shows Clustering Analysis

**DATA DESCRIPTION**

![download](https://user-images.githubusercontent.com/109536544/206096597-168a21e5-6ec1-4223-835d-0c6b6c22c66a.jpg)


This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled.

**In this project, we were required to do:**

1.Exploratory Data Analysis

2.Understanding what type content is available in different countries

3.Is Netflix has increasingly focusing on TV rather than movies in recent years.

4.Clustering similar content by matching text-based features

**Introduction**

Netflix is the largest online movie and TV show streaming service in the world.
Many countries including but not limited to the United States, India, South Korea, Japan etc. offer its service on a large scale. With its approach of delivering shows and movies, the sales of Netflix has grown exponentially in recent past. The platform has also created its own recommender system to understand what types of movies and TV shows the users would like to watch, what kind of style of cinematography they liked the most, and how they consume their favorite TV shows. With the use of data analysis, more users attracted to it, and many of them now spend the majority of their time on Netflix binge-watching TV shows and Movies.

**Data Pre-Processing**

Dealt with null values . Columns having very few null values such as date_added and rating, we have remove those null values. Also, duplicate values are not present in the dataset.

**Feature Engineering**

we extracted some new features in the form of day_added, month_added , year_added from date_added column. Genres are extracted from the listed_in column and redefined accordingly.

**1.EDA**

As part of Exploratoy Data Analysis we have got some interesting findings such as 69.1% of the content available on the platform are movies and remaining 30.9% are TV shows. Growth in the number of movies on Netflix is much higher than TV shows. The highest number of movies and tv shows got added in 2019 and 2020. October, November, December and January are months in which many shows and movies get uploaded to the platform. Most of the content gets uploaded in the beginning and the middle of the month. USA, India, and Uk create more than half of the tv shows and movies on the platform. Most content on Netflix is rated for Mature Audiences and over 14 years old. Top Genres on Netflix are found to be : Drama, Comedy, Documentary, Action and Adventure, Romance etc.

**2.Understanding what type content is available in different countries**

 In our analysis, we found out that United States is a leading producer of both types of content which is obvious as Netflix is US Based company. It is followed by India where most of the content is in the form of movies. Drama is the most produced genre in a lot of Non-English  speaking countries. Comedy is the most produced genre in English speaking countries like United States of America and United Kingdom and Canada.
 
 **3.Is Netflix has increasingly focusing on TV rather than movies in recent years.**
 
 We have found that While the no of movies signed were higher, it can be seen that the TV shows signed per year is catching up with the movies signed year by year.
 
 **4.Clustering similar content by matching text-based features**
 
 Under this, we performed KMeans and Hierarchial Clustering . We also performed Topic Modelling using LDA technique.
 

**Clustering** 

we perform Clustering analysis in the form of K-Means Clustering and 
Hierarchial clustering . In K-Means Clustering, highest silhouette score of 0.909 is produced with 8 Clusters . Iin Hierarchial Clustering , we got the highest score of 0.90 at the distance of 20 with 8 clusters.

**Topic Modelling**

we perform Topic Modelling with the help of Latent Dirichlet
Allocation method and seven topics were found to be the most suitable by
comparing Coherence Score for different topic number. Some of the top words
among all the 7 topics are Drama, Comedy, Romance, Love, Life, Thriller,
Horror, Young, Music, World, Reality, Life etc.






