# Movies-ETL

Overview of Project

In this analysis, we are creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. In the first deliverable, we wrote an ETL (Extract, Transform and Load) function to read the three Data files for this project. The three data files referenced in this project are Wikipedia data, Kaggle/Movies Metadata and Ratings Data. 

In the second deliverable, we focused on the cleaning the movie using some of the information we used in the first deliverable. We cleaned four columns in this deliverable – the box office column, the budget column, the release date column, and the running time column. 

In the third deliverable, we extracted and transformed the data into separate DataFrames and then merged the Kaggle/Movies Metadata with the Wikipedia movies DataFrame to create the Movies DataFrame. Then we merged the MovieLens rating DataFrame with the Movies DataFrame to create movies_with_ratings_df.

In the fourth and final deliverable, we used the information we gathered in the third deliverable, refactored our code and imported the Movies DataFrame and MovieLens Rating DataFrame CSV data into PostgreSQL database. After successfully running and importing the data, we ran movies and ratings queries to ensure the movies table has the correct row count and the ratings table has the correct rows count. 


RESULTS
According to the movie query we ran in SQL, there are 6,052 rows for the movies and there are 26,024,289 rows for the ratings query.

<img width="758" alt="movies_query" src="https://user-images.githubusercontent.com/85265504/152091240-64536d88-3797-4099-9588-d50a99178db3.png">

<img width="758" alt="ratings_query" src="https://user-images.githubusercontent.com/85265504/152091257-e92be3e7-8f1d-47a4-a835-baeff011d791.png">
