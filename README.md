# Movies-ETL

Overview of Project
In this analysis, we are creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. In the first deliverable, we wrote an ETL (Extract, Transform and Load) function to read the three Data files for this project. The three data files referenced in this project are Wikipedia data, Kaggle/Movies Metadata and Ratings Data. 

In the second deliverable, we focused on the cleaning the movie using some of the information we used in the first deliverable. We cleaned four columns in this deliverable – the box office column, the budget column, the release date column, and the running time column. 

In the third deliverable, we extracted and transformed the data into separate DataFrames and then merged the Kaggle/Movies Metadata with the Wikipedia movies DataFrame to create the Movies DataFrame. Then we merged the MovieLens rating DataFrame with the Movies DataFrame to create movies_with_ratings_df.

In the fourth and final deliverable, we used the information we gathered in the third deliverable, refactored our code and imported the Movies DataFrame and MovieLens Rating DataFrame CSV data into PostgreSQL database. After successfully running and importing the data, we ran movies and ratings queries to ensure the movies table has the correct row count and the ratings table has the correct rows count. 


RESULTS
According to the movie query we ran in SQL, there are 6,052 rows for the movies and there are 26,024,289 rows for the ratings query.

https://github.com/dmoronfolu/Movies-ETL/blob/5cd2b76d24873abbae269df853cc0f45d7133521/movies_query.png

https://github.com/dmoronfolu/Movies-ETL/blob/5cd2b76d24873abbae269df853cc0f45d7133521/Resources/ratings_query.png

![image](https://user-images.githubusercontent.com/85265504/129462030-ba08a47d-0821-40fe-b939-b6a646ed7a47.png)



