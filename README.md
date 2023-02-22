SQL_VideoGames - Project from Datacamp

The project asks to explore the top 400 best-selling video games created between 1977 and 2020 by comparing a dataset on game sales with critic and user reviews to determine whether or not video games have improved as the gaming market has grown.
The database contains two tables. Datacamp have limited each table to 400 rows for this project. Complete dataset with over 13,000 games can be found in Kaggle.

The two tables are:

game_sales (7 columns: game, platform, publishes, developer, games_sold, year)

reviews (3 columns: year, critic_score, user_score)

Problem #1:
Finding the ten best-selling video games in game_sales.

Problem #2:
Determining how many games in the game_sales table are missing both a user_score and a critic_score.

Problem #3:
Finding the years with the highest average critic_score, ordering the result from highest to lowers average critic_score.

Problem #4:
Finding game critics' ten favorite years, this time with the stipulation that a year must have more than four games released in order to be considered.

Datacamp created two additional tables with the results of previous two queries:

top_critic_years (2 columns: year, avg_critic_score)

top_critic_years_more_than_four_games (3 columns: year, num_games, avg_critic_score)

Problem #5:
Finding the years that were on the first critics' favorite list (Problem #3) but not the second (Problem #4), ordering the result from highest to lowest average critic score.

Problem #6:
Creating a query very similar to the one used in Problem #4, except this one will look at user_score averages by year rather than critic_score averages.

Problem #7:
Create a list of years that appear on both the top_critic_years_more_than_four_games table and the top_user_years_more_than_four_games table. These are excellent years where both critics and players agreed that the games listed are in top ten.

Problem #8:
Adding a column showing total games sold in each year to the table created from the previous problem to see whether sales were good in those years. 

