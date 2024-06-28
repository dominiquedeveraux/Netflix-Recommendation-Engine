# Netflix-Recommendation-Engine
Created a recommendation of movies based on release_year and ratings that are PG and PG-13.


**data_loading:** Load the data from "/tmp/netflix_titles.csv" into a pandas DataFrame.
**data_cleaning:** Remove any irrelevant columns or handle missing values if necessary.
**data_wrangling:** Filter the DataFrame to include only movies with ratings "PG" and "PG-13".
**data_analysis**: Analyze the relationship between release year and ratings to identify trends or patterns.
**feature_engineering:** Create new features or transform existing ones to improve the recommendation process (e.g., grouping movies by release year or rating).
**model_training:** Choose a suitable recommendation algorithm (e.g., collaborative filtering, content-based filtering) and train it on the prepared data.
**model_evaluation**: Evaluate the performance of the trained model using appropriate metrics.
**finish_task:** Generate a list of recommended movies based on the model's output and present it in a user-friendly format.

The goal was to build a recommendation system for young adults based on year of release, PG and PG-13 movies. 

Recommendation Systems:

Recommendation: Takes user or item data, takes an algorithm and creates preferences.

Steps to make a recommendation engine: 
1. Candidate Generation - take dictionary into a subset
2. Scoring - rank candidates in order
3. Reranking
