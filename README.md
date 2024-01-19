# CS-210-Project
Film Rating Analysis 

1. Data Collection
To compile data for my film rating analysis, I utilized web scraping. First, I created a movie list on the Letterboxd site containing films I've watched. The web scraping code used for data retrieval can be found here.

2. Exploratory Data Analysis (EDA) EDA was crucial for cleaning and understanding the dataset before hypothesis testing. Notable results include: A distribution graph illustrating 'Popularity_Category' and 'Owner_rating_category.' A bar plot showcasing the average user ratings for the top 10 countries. A line plot displaying average ratings of movies over the years. A stacked bar chart comparing owner and average ratings for the top 10 genres. A heatmap visualizing correlations among numerical columns.
   
3. Hypothesis Testing The hypothesis involved the perceived decline in Oscar film quality and its impact on personal preferences. The test compared ratings of films nominated for Oscars and Cannes. The results indicated a significant difference in owner ratings between the two groups, supporting the hypothesis.
 4. Machine Learning In support of the primary hypothesis, machine learning (RandomForestRegressor) predicted ratings for unwatched films. Two datasets, df_filled_oscar and df_filled_cannes, were created. Hypothesis testing on these datasets revealed a significant difference in predicted ratings, further supporting the main hypothesis.
 
Project Website: https://sellmanyilmaz.blogspot.com/2024/01/1-data-collection-i-obtained-data-via.html
