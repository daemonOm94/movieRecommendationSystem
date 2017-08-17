# movieRecommendationSystem
Our ML system would train on movie ratings database and would do the following :
1. Recommend movies to existing users based on their past ratings of other movies.
2. Recommend movies to that are similar to each other( based on movie features )
3. Recommend top 10 movies to watch ( based on the average of ratings given by users )

User past ratings of movies can be viewed at movies_ratings_data_set.csv. Also information about movies such as their title, movie_id, genre etc. can be viewed at movies.csv. This can be used for verification purpose when we suggest similar movies to users.

Building ML system :
1. For training the system, run train_system.py
2. For objective 1, run suggest_movies_to_users.py
3. For objective 2, run suggest_similar_movies.py
4. For objective 3, run top_movies_recommendation.py
