# Unsupervised-ML---Netflix-Movies-and-TV-Shows-Clustering
Project Overview
This project aims to analyze the content available on Netflix as of 2019. The dataset consists of TV shows and movies collected from Flixable, a third-party Netflix search engine. The analysis focuses on various aspects, including the types of content available, their distribution across different countries, and clustering similar content based on text-based features. The insights gained from this analysis can help in understanding trends and patterns in Netflix's content library.

Dataset
The dataset includes the following columns:

show_id: Unique ID for each show
type: Type of content (Movie or TV Show)
title: Title of the content
director: Director of the content
cast: Cast members
country: Country of origin
date_added: Date the content was added to Netflix
release_year: Year the content was released
rating: Content rating
duration: Duration of the content
listed_in: Categories/genres the content is listed under
description: Description of the content
Goals and Steps
1. Exploratory Data Analysis (EDA)
  1. Understand the distribution of content types (Movies vs. TV Shows)
  2. Analyze the duration of movies and TV shows
  3. Examine the distribution of content across different countries
  4. Identify popular genres and categories
  5. Understand the distribution of content by release year and date added
2. Clustering Similar Content
  1. Use text-based features such as titles, descriptions, and listed_in categories to cluster similar content
  2. Perform text preprocessing (cleaning, tokenization, stopword removal, lemmatization)
  3. Apply TF-IDF vectorization to convert text data into numerical features
  4. Use PCA for dimensionality reduction
  5. Apply K-means clustering to group similar content
  6. Evaluate clustering performance using metrics like Silhouette Score and Davies-Bouldin Index
4. Insights and Visualization
  1. Visualize the distribution of content types, genres, and countries
  2. Analyze the trends in content addition over the years
  3. Identify the most frequently used words in titles and descriptions
  4. Interpret and visualize the clusters to identify common themes and patterns
