# P2-Popular-Movies

_Project 1 of Udacity's Android Developer Nanodegree_ 

## Project Overview
Build an app to allow users to discover the most popular movies playing. The development of this app is split in two stages. 
In this stage 1 I built the core experience of the movies app.

The app:

- Presents the user with a grid arrangement of movie posters upon launch.
- Allows the user to change sort order via a setting:
The sort order can be by most popular or by highest-rated
- Allows the user to tap on a movie poster and transition to a details screen with additional information such as:
    * original title
    * movie poster image thumbnail
    * A plot synopsis (called overview in the api)
    * user rating (called vote_average in the api)
    * release date

## Installation

- You will first need to apply for an API key (v3 auth) from [TheMovieDB](https://www.themoviedb.org/)
- You then need to enter your API key in the project's gradle.properties file:
    ```API_KEY="(your API key)"```
