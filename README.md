The movie recommendation system uses a content-based filtering approach to suggest movies to users based on their similarity to a selected movie.
By leveraging a TF-IDF vectorizer and the Sigmoid kernel, the system computes pairwise similarity scores between movies. 
It then recommends the top 10 movies with the highest similarity scores, excluding the selected movie itself. 
This approach allows users to discover movies that share similar themes, genres, or content with their favorites, enhancing their viewing experience.
