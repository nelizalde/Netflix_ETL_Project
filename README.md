# Netflix_ETL_Project

This ETL project combines multiple Netflix data sources from Kaggle into a single postgres sql table.

## Data Sources

Data sources consist of both TV shows and movies

[1: List of TV shows on multiple streaming services](https://www.kaggle.com/ruchi798/tv-shows-on-netflix-prime-video-hulu-and-disney)

[2: List of Movies on multiple streaming services](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney)

[3: List of TV shows and Movies on Netflix (through January 2021)](https://www.kaggle.com/shivamb/netflix-shows)

Sources 1 and 2 include ratings from Rotten Tomatoes and IMDb.  Source 3 includes TV/Movie Ratings (MPAA) and Target Audience Age.

## Methods

Jupyter notebook used to extract data from CSV files, transform data using Pandas, and load data into a postgres sql database.

Excel file used to plot out business rules for source data files to prepare for final database table.

SQL schema included to create database, create new empty table, and confirm table schema (SELECT statement).

Output folder contains a CSV copy of the final table from the database and an Audit.html file to track the number of records removed (null values, non-Netflix titles) and how long portions of the ETL process took to complete.

## Collaborators

This project completed by 
