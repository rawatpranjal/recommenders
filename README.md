### Recommender Systems

Explore key recommender system approaches with practical examples.

---

### Dataset

Using the **MovieLens Latest Small Dataset** (`ml-latest-small`):
- **movies.csv**: Metadata about movies (`movieId`, `title`, `genres`).
- **ratings.csv**: User ratings for movies (`userId`, `movieId`, `rating`, `timestamp`).

---

### Key Methods

| **Approach**                    | **Content-Based Filtering**                  | **User-Based Collaborative Filtering**     | **Item-Based Collaborative Filtering**     | **Matrix Factorization (SVD)**             | **Neural Collaborative Filtering (NCF)**   |
|---------------------------------|---------------------------------------------|-------------------------------------------|-------------------------------------------|---------------------------------------------|---------------------------------------------|
| **Goal**                        | Recommend items based on metadata.          | Recommend using similar users' preferences.| Recommend items similar to past interactions.| Decompose user-item matrix into latent factors.| Use deep learning to learn complex patterns.|
| **Data**                        | Item metadata (e.g., genres).               | User-item interaction data.               | User-item interaction data.               | Interaction matrix (explicit or implicit).  | Interaction matrix (explicit or implicit).  |
| **Strength**                    | Handles cold-start items well.              | Captures collaborative preferences.        | Effective for item similarity.            | Captures hidden relationships.              | Models non-linear patterns effectively.     |
| **Weakness**                    | Struggles with new users.                   | Requires overlapping users.               | Limited diversity in recommendations.     | Sensitive to hyperparameters.               | High complexity and resource demand.        |
| **Scalability**                 | Scales with metadata; item-limited.         | Struggles with many users.                | Scales better than user-based.            | Scales for dense matrices; needs decomposition.| Requires large data, optimized hardware.    |
| **Example**                     | "You liked Sci-Fi, so try *Blade Runner*."  | "Users like you enjoyed *The Dark Knight*."| "If you liked *Inception*, try *Interstellar*."| "Predict ratings for unseen movies."        | "Recommend likely interactions."           |