# als-movie-recommender
A movie recommendation system built using PySpark and the ALS algorithm. This project predicts movie ratings and recommends movies based on user ratings

# Movie Recommendation System

This repository contains a movie recommendation system built using the Alternating Least Squares (ALS) algorithm with PySpark. The system recommends movies to users based on their past ratings.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project demonstrates how to build a collaborative filtering-based recommendation system using the ALS algorithm. The system predicts ratings for movies that users have not yet rated and recommends movies to users based on these predictions.

## Dataset


The dataset used in this project consists of user ratings for movies. The dataset includes the following files:
- `movies.csv`: Contains movie information (movieId, title, year).
- `ratings.csv`: Contains user ratings for movies (userId, movieId, rating, timestamp).
- `films.csv`: Contains a list of movies liked by a specific user (Name, Year).

The `films.csv` file is extracted from [Letterboxd](https://letterboxd.com/), which is a social platform for sharing your taste in films.

## Installation
To run this project, you need to have Python and PySpark installed. You can install the required libraries using pip


## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/USERNAME/movie-recommendation.git
   cd movie-recommendation
## Model Evaluation 
The performance of the ALS model is evaluated using two metrics:

Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
After training the model, the following performance metrics were obtained:

RMSE: 0.8839
MAE: 0.6798
These metrics indicate how well the model predicts the movie ratings.

## Contributing
If you have any suggestions or improvements, please feel free to submit a pull request.

## License
This project is licensed under the MIT License.

