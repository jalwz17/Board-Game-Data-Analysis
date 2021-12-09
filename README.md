# Board-Game-Data-Analysis

This dataset contains data collected on board games from the BoardGameGeek (BGG) website in February 2021. BGG is the largest online collection of board game data which consists of data on more than 100,000 total games (ranked and unranked).

The voluntary online community contributes to the site with reviews, ratings, images, videos, session reports and live discussion forums on the expanding database of board games.

This data set contains all ranked games (~20,000) as of the date of collection from the BGG database. Unranked games are ignored as they have not been rated by enough BGG users (a game should receive at least 30 votes to be eligible for ranking).

There are a total of 14 variables: 
 - ID (BoardGamesGeek ID), 
 - Name
 - Year Published
 - Min Players (Min suggested players)
 - Max Players (Max suggested players)
 - Play Time (Average play time suggest by game creator)
 - Min Age (Age rating)
 - Users Rated (Amount of users who reviewed the game)
 - Rating Average
 - BGG Rank (BoardGamesGeek ranking)
 - Complexity Average (Complexity rating)
 - Owned Users (Amount of users who said they own the game)
 - Mechanics
 - Domains (Game subgenre)

In the past, my family and I would try to play a board game every two weeks, and this would be considered as one of our "family times". So when growing up, these were some of my most cherished moments. After every game, we would always discuss how it went and occasionally give it a rating. This would determine if we would play it again in the future.

Therefore I want to analyze this data set about board games.

I have identified my tasks:

1. What is the `Average_Rating` for the top 4 most frequently used `Mechanics` and `Domains`? 

2. What commonalities do the most successful (top 100) board games have?

3. Create a line that can predict a board game `Average_Rating` based on its features with linear regression from the top 100 board games (excluding the following variables: `ID`, `Name`, `Users_Rated`, and `BGG_Rank`).
