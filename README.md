# Recommendation Algorithm

## Authors
[Max Popper](https://github.com/maxpopper), 
[Jarret Baum](https://github.com/Jarretbaum), 
[David Castano](https://github.com/Davidcastanoe), and
[Anthony Banda](https://github.com/bandaexpress)

## Overview
The aim of the project is to uncover correlations within commercial movie data. We’ll look at movie genres and ratings from the year 2000 forward and determine relationships between variables to provide recommendations.

## Features
Item-based Recommendation: Utilizes item characteristics and user ratings to generate recommendations.

## Installation
Dependencies needed:
- import pandas as pd
- from sklearn.cluster import KMeans
- import numpy as np
- 

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

## License

## Citation 
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872


## Resources
This and other GroupLens data sets are publicly available for download at http://grouplens.org/datasets/.
