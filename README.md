# Final Project: Tableau

## Project/Goals
To explore, understand, and visualize a provided dataset.

## Process
Select a dataset: Fifa 18 player ratings (video game)
Feature creation:  Best position & Player Type (Attacker, Midfielder, Defender, Goalkeeper)
Feature deletion: Rating by position, image files.
Intro EDA: Understanding player value, nationality, rating distribution, age distribution, and beyond.
Attempt meaningful questions:  Skills by position, where to scout, when to purchase players, player type with the most value, and where to scout affordably.

## Results
Option 2: Fifa 18 player ratings. 
The visualizations were largely focused around EDA.  It was difficult to ask a meaningful question given the limitations of the dataset. As such, most of the visualizations explore cursory relationships between features.  Upon later reflection, I ought to have limited my scope to ask and answer meaningful questions within the game, rather than looking to demonstrate trends outside of the dataset.

Visualizations:
1. Players by nationality:  Map: Where in the world are most players from.
2. Ratings:                 Histogram: What is the distribution of talent (overall rating)
3. Positions:               Bar Chart: What is the distribution of player types
4. Wage by Rating:          Scatterplot:  What is the trend for player wages (polynomial) by player type. 
5. Value by Rating:         Scatterplot:  What is the trend for player value (polynomial) by player type. 
6. Value by age:            Combination: histogram and line: compare distributions of player value and age
7. Value-age cluster:       Histogram:  Clustering shows 4 primary phases to a player's career, and when they most commonly occur by age.
8. Player Rating List:      Bar Chart: Demonstrate Top N Parameter filtering & interactivity.
...



## Challenges 
Context:  
The dataset was curated and massaged for use in the video game.  So trends regarding player value, growth, talent, and distribution were only meaningful within the context of the game. Subsequently, much of this analysis only confirmed obvious, cursory trends within world football (soccer).
I wanted and struggled to ask a meaningful question with global significance, but that was not within the scope of the dataset.  Upon later reflection I should have adjusted my scope to answer questions that are meaningful within the game. 

Modeling:  
The ability to visualize data quickly was useful but did not feel sufficient for meaningful analysis. 

## Future Goals
Interactivity:
More time should be spent building interactive and meaningful dashboards.  This would more aptly demonstrate the capabilities of Tableau and my understanding of the techniques taught.

Connectivity: 
Connecting to outside datasets, such as population distributions by country, video game sales, or player popularity ratings would provide additional  meaningful layers for analysis.

Question Selection:
The context and limitations of the dataset felt insurmountable because I attempted to answer a meaningful question outside of the videogame.  In actuality, I should have reduced my scope to instead answer how to best play the game.

Data Curation:
The majority of the players had ratings that were insignificant (<75 OVR), it may have been useful to focus on the highest rated players in the game since they will yield the most attention from  video game players.