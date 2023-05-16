# **Movies Website (Backend)**

## Overview

The API provides endpoints to retrieve movie data from the 'movie-api-db', a MongoDB database. Additionally, it allows for submitting movie reviews through a POST request to localhost:8080/api/v1/reviews. The submitted review is then stored in the 'movie-api-db' database.

## API Endpoints

The following API endpoints are available:

* GET /api/v1/movies: Retrieves a list of movies from the 'movie-api-db' database.
* GET /api/v1/movies/{imdbId}: Retrieves a single movie from the 'movie-api-db' by the imdbId.
* POST /api/v1/reviews: Submits a movie review to be stored in the 'movie-api-db' database.