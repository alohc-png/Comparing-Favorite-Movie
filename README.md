# Talking Data: Comparing Favorites

### Project Requirements
The project has:
- A variable to store and print the data of your favorite movie.
- .loc to filter the data set to a genre, and store it in a new variable.
- Calculates the min, max, mean, and median of a column.
- Prints how the min, max, mean, and median compare to your favorite movie's value.
- A histogram and use a print statement that describes it.
- A scatter plot and a print statement that describes the relationship between two variables.


###  Attributions
The rotten_tomatoes_movies.csv data was originally scrapped by Stefano Leone and is available on Kaggle for CC0:Public Domain Use: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset?select=rotten_tomatoes_movies.csv


## File Overview

### ← main.py
This is where you will write your main program.

### ← rotten_tomatoes_movies.csv
This is a csv file containing data scraped from Rotten Tomatoes by Stefano Leone. The data was made modified to make student usability easier. Modifications include: Creating the year_released column based on original_release_date, dropping NA values, and selecting out the columns: movie_title, year_released, critic_rating, audience_rating, genres.