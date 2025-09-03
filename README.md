This repository features a content-based movie recommendation system built with Pandas and Scikit-learn. The system recommends movies based on the following logic:

It creates a feature "soup" by combining the names of the top 3 cast members and the director for each movie.

It converts this text data into a feature matrix using TfidfVectorizer.

The similarity between movies is calculated using the cosine_similarity metric.

When a user inputs a movie title, the system returns a list of the top 5 most similar movies.
