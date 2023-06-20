# Movie Analysis on Box Office Data

**Authors**: 
## Overview

This project aims to analyze the box office data retrieved from various different databases. The ultimate goal of this project is to provide 3 actionable recommendations to our company's new movie studio on the type of future films to create.

## Business Situation

Evaluating the box office data on various movies is very important for the new movie studio to start planning for the first movie to film. Different factors such as most popular genre of the movie, production budget, and release date can greatly influence how well a film does in the market, and how much profit it makes. Therefore, analyzing the box office data prior to filming and releasing a new movie can help the new movie studio maximize revenue and plan for the future film. 

## Data Information

Different data sets are gethered from various sources including:

[Box Office Mojo](https://www.boxofficemojo.com/), [IMDB](https://www.imdb.com/), [Rotten Tomatoes](https://www.rottentomatoes.com/), [TheMovieDB](https://www.themoviedb.org/), and [The Numbers](https://www.the-numbers.com/).

These data files exist in various formats, such as CSV (comma-separated values) TSV (tab-separated values), and (SQLite databse).

## Methods

Collectively, we want to apply some filters to focus on a subset of the dataset gathered for the purpose of this project. First, we decide to analyze from the movies that were **released between 2010 and 2018**, because we want to apply the same range of release dates across all databases. We also merge different databases together by completing an **inner join**. Therefore, we focus on movies that are present in both databases.