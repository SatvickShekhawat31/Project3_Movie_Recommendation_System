# 🎬 Movie Recommendation System

## 📌 Overview

This project is a **content-based movie recommendation system** built using Python.
It suggests movies similar to a user’s input by analyzing features like genres, keywords, cast, tagline, and director.

---

## 🚀 Features

* Recommends movies based on similarity
* Uses **TF-IDF Vectorization** for text processing
* Computes similarity using **Cosine Similarity**
* Handles missing data efficiently
* Suggests top 30 similar movies

---

## 🧠 How It Works

1. Load dataset (`movies.csv`)
2. Select important features:

   * genres
   * keywords
   * tagline
   * cast
   * director
3. Combine all features into a single text
4. Convert text into numerical vectors using TF-IDF
5. Calculate similarity between movies using cosine similarity
6. Take user input and recommend similar movies

---

## 🛠️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Scikit-learn

---

## 📂 Project Structure

```
movieRec/
│── movies.csv
│── project.ipynb
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/movieRec.git
```

2. Install dependencies

```bash
pip install numpy pandas scikit-learn
```

3. Run the notebook or script

4. Enter a movie name when prompted:

```
Enter the movie name:
```

---

## 💡 Example

**Input:**

```
Avatar
```

**Output:**

```
1. Guardians of the Galaxy  
2. Star Trek  
3. John Carter  
...
```

---

## ⚠️ Notes

* Input movie name should be close to dataset titles (spelling matters)
* Uses `difflib` for approximate matching

---

## 🔮 Future Improvements

* Add web interface (Flask / Django)
* Improve recommendation accuracy
* Add posters and UI
* Deploy online

---

## 👨‍💻 Author

Satvick Shekhawat
