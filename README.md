# MovieRecommandation
 
## DataSets
Download from here https://www.kaggle.com/grouplens/movielens-20m-dataset

## Collaborative Filtering
Collaborative Filtering simply put uses the "wisdom of the crowd" to recommend items.
Item based collaborative filtering uses the patterns of users who liked the same movie as me to recommend me a movie (users who liked the movie that I like, also liked these other movies).
Recommendation based on user's input of any movie present in the dataset.

## Data
### rating.csv that contains ratings of movies by users:
userId,movieId,rating,timestamp
### movie.csv that contains movie information:
movieId,title,genres


## Cosine Similarity
Also known as vector-based similarity, this formulation views two items and their ratings as vectors, and defines the similarity between them as the angle between these vectors:
itembased-cosine


## Recommender
User enters his favourite movie (or the movie on the basis of which he wants the system to recommend movies)
Based on the user's input, recommendation is made by sorting the similarities in descending order
