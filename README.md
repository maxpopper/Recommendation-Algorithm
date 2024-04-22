# Recommendation Algorithm

## Authors
[Max Popper](https://github.com/maxpopper), 
[Jarret Baum](https://github.com/Jarretbaum), 
[David Castano](https://github.com/Davidcastanoe), and
[Anthony Banda](https://github.com/bandaexpress)

## Overview

Machine learning plays a part in our lives every day, whether we're aware of it or not. In class, we learned about ML under the context of regression, neural networks, and picture identification, but there are countless additional uses. Content=based recommendation algorithms are great examples of ML that add value to our lives. Platforms like YouTube, Spotify, and Instagram have spent years tailoring their respective algorithms to ensure their users find more content that they will like. Keeping this in mind, our aim for this project is to create a recommendation algorithm to suggest 10 similar movies based on 1 user-submitted movie title.

Our dataset contains 11,000+ movies from the year 2000 until 2023, and takes key data points like *Year*, *Average User Rating*, *Rating Count*, and *Genres* into consideration when deciding what movies to recommend. Ultimately, our goal was to create an algorithm inspired by the ones used by Netflix, Hulu, and other movie streaming platforms to recommend movies that their users might like.

## Features
Item-based Recommendation: Utilizes item characteristics and user ratings to generate recommendations.

## Installation
Dependencies needed:
- import pandas as pd
- from sklearn.preprocessing import MinMaxScaler, OneHotEncoder
- from sklearn.neighbors import NearestNeighbors
- from fuzzywuzzy import process
- from langdetect import detect

## Steps

1. Data Preparation
Files are easy to read CSVs.
File size has been reduced to a manageable size (from 335MB to 1.2MB )

![image](https://github.com/maxpopper/Recommendation-Algorithm/assets/17518802/1ac301fa-1e16-4e91-a826-e712eb5edfb2)

The dataset describes 5-star rating and free-text tagging activity from [MovieLens](https://movielens.org/), a movie recommendation service. It contains 33832162 ratings and 2328315 tag applications across 86537 movies. These data were created by 330975 users between January 09, 1995 and July 20, 2023. This dataset was generated on July 20, 2023.

Users were selected at random for inclusion. All selected users had rated at least 1 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

3. Training the model
Adjusting hyperparameters and configurations for optimal performance.

4. Generating recommendations
Utilize the trained model to generate recommendations for movies.

## Example



## Evaluation
Precision: Measure of the accuracy of the recommended items

## Citation 
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872

## Resources
This and other GroupLens data sets are publicly available for download at http://grouplens.org/datasets/.
