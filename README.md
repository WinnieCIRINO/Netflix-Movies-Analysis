# Netflix-Movies-Analysis
This repository focuses on analyzing a movie dataset to uncover insights into movie durations, trends of movies over the years, and other relevant metrics. The analysis aims to provide actionable insights for content creators, movie sellers and people interested in understanding movie consumption patterns.

## Dataset
The dataset includes information about  Movies available on Netflix, including details such as movie duration, genre, release year and country of origin , country of release.

## Analysis
The analysis includes the following aspects:

**Movie Durations by Year** : Examination of how movie durations have changed over the yearss.

**Short Movies Analysis** : Identification of movies with a duration of less than 60 minutes.

**Scatter Plot of Movie Duration** : Visualization of the relationship between movie release year and duration.

**Movie Population Trends** : Examinations of movie genres and their popularity over different time periods.

## Key Metrics

**Total Duration of Movies** :  Sums of moview durations of different catergories

**Movie Genre Statistics** : Insights into the distribution of different movie genres over the years. 

## Requirements

**Python** : Used for data cleaning, analysis and visualization.

**Pandas** : Used for data manipulation and DataFrame operations.

**MatPlotlib** : Used for creating visualization such as scatter plots and line plots.

## Tasks Overview
1. Create a list of years from 2011 to 2020 and a list durations of the average movie lengths our friend provided 
(103, 101, 99, 100, 100, 95, 95,96, 93. and 90) Create a dictionary movie_dict, with the keys years" and "durations"
 and the values set to your lists years and durations Print and inspect the dictionlsy to ensure was created correctly.

2. Import pandas using its usual alias, pd. 
Create  a DataFrame durations_df using your movie_dict dictionary you created in the previous step.

3. Import matplotlib.pyplot under the alias plt 
Create a line plot of the data with the years column of durations _df on the x|axis, and the durations column on the y- axis.
 Add the title Netflix Movie Durations 201 1-2020" to your plot.

4. Create another DataFrame, netflix_df, this time using the CSV file our friend provided us with, 
available at the path "datasets/netflix_data.csv" Print the first five rows of the DataFrame to inspect the data 
and ensure it was created successfully.

5. Subset the netflix_df DataFrame such that only rows where the type is a "Movie" are preserved. 
Assign the result to netflix_df_movies_only. Subset the netflix_df_movies_only DataFrame to preserve only the columns 
title, country, genre, release_year, and duration. Assign the result to netflix_movies_col_subset 
Print the first five rows of netflix_movies_col_subset.

6. Using your netflix_movies _col_subset DataFrame, create a scatter plot, placing the release_year on the x-axis 
and the movie duration on the y-axis tons Add a title to your plot: "Movie Duration by Year of Release" Show the plot.

7. Subset netflix_movies_col_subset to create a new DataFrame short _movies containing only movies that have a duration 
fewer than 60 minutes Print the first 20 rows of short_movies to get a good overview of the types of films with a short duration.

8. Initialize an empty list called colors to store our different color values Use a for loop to iterate through 
the netflix_movies_col_subset DataFrame's rows and append colors to your colors list based on the following conditions: 
lf the genre is " Children", append "red" 
lf the genre is "Documentaries". append "blue" 
lf the genre is "Stand-Up", append "green".
lf the genre is any other genre, append "black"
Print the first 10 values of your colors list to inspect the results

9. Using the data contained in netflix_movies _col_subset, plot the same scatter plot 
as you did in Task 6, but with a few modifications 
Color the points on the scatter plot using your colors list you defined in the previous step 
Add a title Movie duration by year of release". an x-axis A label "Release year", 
and a y-axis label "Duration (min Show the plot.

10. Provide your answer to the question " Are we certain that movies are getting shorter?" in the form of a string DATA SETS.


## Access the Dataset
The dataset used in this analysis can be accessed [here](https://drive.google.com/drive/folders/1HzNqeUsQSO9-dUPr7KrTkTqIjIs9sae4?usp=drive_link)
