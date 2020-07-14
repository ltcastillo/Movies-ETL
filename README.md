# Movies-ETL
# Challenge Analysis Assumptions
-Assumption 1: We can assume that both of the CSV's have a column that is named "imdb_id" This explains why we inserted the try-except in the event any csv doesn't have the "imdb_id" column. 

-Assumption 2: Function can only work if user running it has all files called out.

-Assumption 3: When cleaning out the movie data file, we included some key values to try and find alternative titles. We need to assume that we listed out all the key values and alternative titles. If we did not get all of the key values then our data would be need more cleaning. Key values were used to find alternative movie titles - it can be assumed all key valyes and alternative titles were listed - if not, data would need more cleaning. 

-Assumption 4: All data is clean, but if it isn't the functipn will clean it for us
