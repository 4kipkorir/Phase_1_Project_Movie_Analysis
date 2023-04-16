# Microsoft Movie Studio - Movies Analysis

## Overview

This project aims to provide Microsoft, who is entering the movie creation industry, with actionable insights based on data analysis of the movie industry. The analysis is conducted using data from various sources, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.

## Business Understanding

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry. Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
The following key questions are addressed through analysis to enable Microsoft decision makers make an insight full decision:

1. Which movie genre is the most profitable?
2. Is there a correlation between movie budget and profitability?
3. Which movie genre is the most popular among audiences?
4. Among other studios, which movie genre is the most popular?

## Data Understanding and Analysis

Movie data from various sources, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers was used in the analysis, The data is in zippedData folder.

The analysis was conducted using movie data covering the period from 2010 to 2020. The variables used in the analysis included Movie Profits, production_budget, genre of the movie, and rating of the movies. It should be noted that the data had some limitations, such as missing values and inconsistency in genre classification for some movies. As an assumption, the first genre listed for each movie was used for the analysis to overcome this limitation.

The analysis involved data preparation and utilization of Python libraries such as pandas, numpy, and matplotlib, along with SQL to access IMDb database. Different types of visualizations including bar charts, scatter plots, box plots, and line graphs were used to effectively represent the analyzed data.



## Conclusion

The top 5 movie genres that tend to generate higher profits are identified as action, adventure, drama, comedy, and documentaries. However, it's important to note that some movies have multiple genres. Shown in graph below

![image](https://user-images.githubusercontent.com/125445043/232316703-fd9a8277-3158-41d9-a6e1-ca480bcf06ae.png)





The analysis of profits and production budgets shows that while some low-budget movies may have higher profits, some high-budget movies may have low profits, indicating potential outliers and other factors influencing profitability. Further analysis and additional data may be necessary to draw conclusive insights.shown in the graphs below.
![image](https://user-images.githubusercontent.com/125445043/232317051-3cee4165-9aa2-49a4-bf98-347092f4ca60.png)
![image](https://user-images.githubusercontent.com/125445043/232317100-4b342ec1-253c-4cc5-aa84-8ba24fc2cfe4.png)



Action and adventure movies have consistently ranked among the most profitable genres since 2010, indicating their popularity among audiences and their potential for generating high profits. shown in the graph below.
![image](https://user-images.githubusercontent.com/125445043/232317350-5da87a0c-6e1a-4eb4-979f-a66cc7d55d89.png)


The top 5 most popular movie genres among viewers are identified as action, adventure, history, crime, and fantasy, indicating a strong audience interest in these types of movies. show in graph below
![image](https://user-images.githubusercontent.com/125445043/232317475-5c1154ef-bb86-4855-bb6f-57c97fc3bffe.png)

Analysis of data from 10 studios shows that half of the studios have a preference for action movies as their favorite genre, followed by drama, indicating a diverse range of genre preferences among studios.
![image](https://user-images.githubusercontent.com/125445043/232317651-ebc91df6-212c-4c1f-97d8-ff5590518176.png)

##Recommendations
Based on the analysis, the following recommendations are provided for Microsoft's new movie studio:

1. Consider focusing on action, adventure, and drama genres as they tend to generate higher profits.
2. Among audiences action,adventure and drama are the most popular.
3. Conduct further analysis and gather additional data to better understand the relationship between production budgets and profits in the movie industry.
4. Studios prefer Action and Drama genre, Monitor and follow the genre preferences of other studios to stay competitive in the market.

