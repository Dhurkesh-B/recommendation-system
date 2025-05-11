# 🎬 Movie Recommendation System

This project is a **content-based movie recommendation system** built using Python and Jupyter Notebook. It asks for your favorite movie and recommends similar movies based on their content features such as genres, keywords, tagline, cast, and director — all extracted from a CSV dataset.

---

## 🚀 Features

* ✅ Asks the user for a favorite movie.
* ✅ Suggests similar movies using content-based filtering.
* ✅ Uses **TF-IDF Vectorization** to analyze movie descriptions.
* ✅ Computes **cosine similarity** between movie vectors.
* ✅ Intelligent typo correction with the help of `difflib`.

---

## 🧠 How It Works

1. Loads a dataset of movies (`movies.csv`) using pandas.
2. Combines important textual features into a single string.
3. Converts text to numerical form using **TF-IDF Vectorizer**.
4. Calculates similarity scores with **cosine similarity**.
5. Recommends top N most similar movies to the one you input.

---

## 💠 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn (TF-IDF & Cosine Similarity)
* difflib (to match close movie names)

---

## 📂 Dataset

The dataset used is a `.csv` file (`movies.csv`) containing movie metadata including:

* Title
* Genres
* Overview
* Cast
* Crew
* Keywords

Ensure your CSV file has these or similar fields for the best results.

---

## 📋 How to Use

1. Clone the repository or download the Jupyter notebook.
2. Make sure `movies.csv` is in the same directory.
3. Open the notebook and run all cells.
4. Enter the name of your favorite movie when prompted.
5. Get a list of similar movie recommendations!

---

## 💡 Sample Output

```
Enter your favorite movie: Avatar

Recommended movies:
1. Guardians of the Galaxy
2. Star Trek
3. John Carter
4. Interstellar
5. The Fifth Element
```

---

## 📌 Notes

* Spelling errors in movie names are automatically corrected using `difflib`.
* You can enhance accuracy by including more detailed movie features in the dataset.

---

