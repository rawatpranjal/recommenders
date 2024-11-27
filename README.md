## Recommender Systems

This repository explores various **recommender system approaches**, showcasing multiple methods to generate movie recommendations. Each approach is implemented with practical code examples and concise explanations.

---

### Datasets

We use the **MovieLens Latest Small Dataset** (`ml-latest-small`), which includes:
- **movies.csv**: Metadata about movies (`movieId`, `title`, `genres`).
- **ratings.csv**: User ratings for movies (`userId`, `movieId`, `rating`, `timestamp`).

Download the dataset from [MovieLens](https://grouplens.org/datasets/movielens/).

---

### Approaches

1. **Simple Weighted Ranking**: Ranks movies by popularity, average ratings, and weighted scores.
2. **Item-Based Collaborative Filtering**: Recommends movies based on item-item similarity.
3. **User-Based Collaborative Filtering**: Recommends movies based on similar users' preferences.
4. **Content-Based Filtering**: Recommends movies using metadata (e.g., genres).
5. **Matrix Factorization (SGD)**: Decomposes the user-item matrix using Stochastic Gradient Descent.
6. **Matrix Factorization (SVD)**: Uses Singular Value Decomposition to predict ratings.

---
