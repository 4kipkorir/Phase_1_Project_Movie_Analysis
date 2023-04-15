# Microsoft Movie Studio - Movies Analysis

## Overview

This project aims to provide Microsoft, who is entering the movie creation industry, with actionable insights based on data analysis of the movie industry. The analysis is conducted using data from various sources, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.

## Business Understanding

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry. Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
The following key questions are addressed through analysis to enable Microsoft decision makers make an insight full decision:

Which movie genre is the most profitable?
Is there a correlation between movie budget and profitability?
Which movie genre is the most popular among audiences?
Among other studios, which movie genre is the most popular?

## Data Understanding and Analysis

Movie data from various sources, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers was used in the analysis, The data is in zippedData folder.

The analysis was conducted using movie data covering the period from 2010 to 2020. The variables used in the analysis included Movie Profits, production_budget, genre of the movie, and rating of the movies. It should be noted that the data had some limitations, such as missing values and inconsistency in genre classification for some movies. As an assumption, the first genre listed for each movie was used for the analysis to overcome this limitation.

The analysis involved data preparation and utilization of Python libraries such as pandas, numpy, and matplotlib, along with SQL to access IMDb database. Different types of visualizations including bar charts, scatter plots, box plots, and line graphs were used to effectively represent the analyzed data.



## Conclusion

The top 5 movie genres that tend to generate higher profits are identified as action, adventure, drama, comedy, and documentaries. However, it's important to note that some movies have multiple genres.

The analysis of profits and production budgets shows that while some low-budget movies may have higher profits, some high-budget movies may have low profits, indicating potential outliers and other factors influencing profitability. Further analysis and additional data may be necessary to draw conclusive insights.

Action and adventure movies have consistently ranked among the most profitable genres since 2010, indicating their popularity among audiences and their potential for generating high profits.

The top 5 most popular movie genres among viewers are identified as action, adventure, history, crime, and fantasy, indicating a strong audience interest in these types of movies.

Analysis of data from 10 studios shows that half of the studios have a preference for action movies as their favorite genre, followed by drama, indicating a diverse range of genre preferences among studios.

Based on the analysis, the following recommendations are provided for Microsoft's new movie studio:

Consider focusing on action, adventure, and drama genres as they tend to generate higher profits.
Among audiences action,adventure and drama are the most popular.
Conduct further analysis and gather additional data to better understand the relationship between production budgets and profits in the movie industry.
Studios prefer Action and Drama genre, Monitor and follow the genre preferences of other studios to stay competitive in the market.

