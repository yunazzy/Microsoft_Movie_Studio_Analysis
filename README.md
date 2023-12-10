# Microsoft Movie Studio Analysis

## Overview
This project has us assisting Microsoft in understanding the movie market. By diving into data from sources like Box Office Mojo and IMDB, we aim to decode what drives box office success. Our objective? Advising Microsoft on the types of movies they should produce for their new studio. The following characteristics are typically good indicators of success for movies: descriptive analysis of budget and production values, runtime, genre, and rating data. We found

## Business Understanding
This project has us assisting Microsoft in understanding the movie market. By diving into data from sources like Box Office Mojo and IMDB, we aim to decode what drives box office success. Our objective? Advising Microsoft on the types of movies they should produce for their new studio. The following characteristics are typically good indicators of success for movies: descriptive analysis of budget and production values, runtime, genre, and rating data. We found

## Data Understanding
### Overview

The project involves analyzing data from various sources to assist Microsoft in understanding the movie market. Data is sourced from Box Office Mojo, IMDb, The Movie Database (TMDb), and The Numbers. The datasets contain information about movies, including details like box office earnings, ratings, genres, production budgets, and more. Preprocessing steps were taken to handle missing values and ensure data consistency.

### Data Sources

- Box Office Mojo: Provides movie-related data, including domestic and foreign gross earnings, studios, and release years.
- IMDb: Offers comprehensive movie details such as titles, genres, release years, ratings, and reviews.
- The Movie Database (TMDb): Contains genre IDs, vote averages, and counts for movies.
- The Numbers: Provides data on release dates, production budgets, and worldwide gross revenue.
### Data Description

The datasets consist of diverse attributes:

+ Box Office Mojo: Features columns like title, studio, domestic and foreign gross, and year. Contains approximately 3387 records.
+ IMDb: Includes movie basics with details on movie ID, title, genres, release year, and runtime. Movie ratings dataset contains ratings and review data.
+ TMDb: Provides columns such as genre IDs, original language, popularity, release date, title, vote average, and vote count.
+ The Numbers: Includes information on release dates, production budgets, domestic and worldwide gross revenue for movies.
### Data Exploration

Initial exploratory analysis involved summarizing statistics, creating visualizations (e.g., bar plots for top studios by total gross revenue, line plots for average runtime per year), and identifying top-rated genres and most voted genres based on average ratings and number of votes.

### Data Preprocessing

Preprocessing steps included handling missing values, converting data types (e.g., converting 'foreign_gross' to numeric and filling missing values with mean), and dealing with null values in 'genres' by replacing them with 'Unknown'.

* Sample Data *

Snippet of Box Office Mojo data:

| Title                             | Studio | Domestic Gross | Foreign Gross | Year |
|-----------------------------------|--------|----------------|---------------|------|
| Toy Story 3                       | BV     | 415,000,000    | 652,000,000   | 2010 |
| Alice in Wonderland (2010)        | BV     | 334,200,000    | 691,300,000   | 2010 |
| Harry Potter and the Deathly...   | WB     | 296,000,000    | 664,300,000   | 2010 |
| Inception                         | WB     | 292,600,000    | 535,700,000   | 2010 |
| Shrek Forever After               | P/DW   | 238,700,000    | 513,900,000   | 2010 |


The data is utilized to derive insights into factors influencing box office success, such as genre preferences, ratings, and revenue trends. It aids in advising Microsoft on the types of movies they should produce for their new studio, enabling data-driven decision-making in the entertainment industry.## Visualizations

## Conclusion
