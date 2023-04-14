# Netflix_Movies_And_Tv_Shows_Clustering
Technical Documentation
![smartphone_netflix_red_background_hd_netflix-1600x900](https://user-images.githubusercontent.com/90696788/232040265-173a8e6e-9092-4cf4-ad7a-661ae8c4a66f.jpg)


Problem Statement :

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

About the Data :
We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle

Dataset info

Number of records: 7787
2.Number of features: 12


Objectives:
Conduct Exploratory Data Analysis.
Try understanding what type content is available in different countries.
Check if Netflix is increasingly focusing on TV rather than movies in recent years.
Clustering similar content by matching text-based features.
Methods used:
Descriptive Statistics.
Data Visualization.
Machine Learning.
Libraries utilized:
NumPy and Pandas - For dataset cleaning and analysis.
Matplotlib, Plotly and Seaborn - For Data Visualization.
SkLearn and nltk - For machine learning and clustering.

Features information:
The dataset contains features like:

show_id : Unique ID for every Movie / Tv Show
type : A Movie or TV Show
title : Title of the Movie / Tv Shows
director : Director of the Movie
cast : Actors involved in the movie / show
country : Country where the movie / show was produced
date_added : Date it was added on Netflix
release_year : Actual Release year of the movie / show
rating : TV Rating of the movie / show
duration : Total Duration - in minutes or number of seasons
listed_in : Generes
description: The Summary description

#Project Work flow:

Importing Libraries
Loading the dataset
Data Summary
Data Cleaning & Data Analysis
Feature selection
Implementing different clustering methods
Conclusion

