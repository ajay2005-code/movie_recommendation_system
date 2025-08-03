# 🎬 Movie Recommendation System (Content-Based Filtering)

This project is a **Content-Based Movie Recommendation System** that recommends similar movies based on textual features like overview, tagline, and genres. It uses **TF-IDF vectorization** and **cosine similarity** to identify and rank the most relevant films.

---

## 📌 Features

- 🔍 Recommends movies similar to a given input title
- 🧠 Uses TF-IDF vectorizer for feature extraction
- 📐 Calculates cosine similarity for ranking
- ✅ Simple, interpretable, and easy to deploy

---

## 📂 Dataset

The project uses a **custom movie dataset** containing movie titles, genres, overviews, and other metadata.

> Note: This dataset was manually downloaded and does **not** use the Kaggle TMDB 5000 dataset. File names may differ (e.g., `tmdb_5000_movies[1].csv`, `tmdb_5000_credits[2].csv`).

You can replace the dataset with any structured movie data that includes:
- Movie titles
- Descriptions/overviews
- Genres or tags


---

## ⚙️ Tech Stack

- 🐍 Python 3.x  
- 📊 Pandas, NumPy  
- ✒️ Scikit-learn (TF-IDF, cosine_similarity)  
- 📚 NLTK (optional for text preprocessing)

---

## 🚀 How to Run

1. Clone the repository or open the notebook in Google Colab.
2. Use the dataset from GroupLens
3. Run the cells in order.
4. Use the `recommend('Movie Name')` function to get top similar movies.

```python
recommend('Toy Story')
