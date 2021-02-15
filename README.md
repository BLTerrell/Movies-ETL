# Movies - Extract, Transform, Load 

## Overview of Project

### Purpose

Amazing Prime wants us to be able to keep up with our database on a daily basis, so our objective is to create an automated pipeline that takes in the data, performs transformations, and loads the data into existing tables.

### Resources

- Data Source: [movies_metadata.csv](Resources/movies_metadata.csv), [wikipedia.movies.json](Resources/wikipedia.movies.json), ratings.csv (file size too large)
- Software: PGAdmin 4.27, PostgreSQL 13.0, Visual Studio Code 1.52.1

## Project Results

### Data Generated

- [movies_query.png](Resources/movies_query.png)
- [ratings_query.png](Resources/ratings_query.png)

## Summary

### Observations

1. The key to generating an expansive function was to start with a smaller function and continue to build on it.
2. Using `.apply(lambda ...)` kept our code clean and saved us from using an excessive amount of lines.
3. Regular expressions are a powerful tool for string matching and extracting meaningful data.
4. Connecting to a database with python is an efficient way to automate your data storage.
