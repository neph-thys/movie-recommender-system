

This project is a content-based movie recommendation system built using Python and machine learning. It leverages metadata from [The Movie Database (TMDB)](https://www.themoviedb.org/) to suggest similar movies based on user input.

*Features*

- Recommend movies based on title similarity
- Uses Count vectorization and cosine similarity
- Clean and modular codebase
- Easy to extend with genres, cast, crew, overview


*How It Works*


1. Data Source: TMDB dataset containing movie titles, overviews, genres, etc.
2. Vectorization: Text data (e.g., overviews) is transformed using `CountVectorizer`.
3. Similarity Calculation: Cosine similarity is computed between movie vectors.
4. Recommendation: Given a movie title, the system returns the top 5 similar movies.


*Tech Stack*


- Python
- Pandas
- Scikit-learn
- TMDB dataset (CSV)

