# 🎬 Movie Recommendation System:-
This is a **Content-Based Movie Recommendation System** developed as part of my **Applied Programming Lab (AP Lab)** project. The system recommends movies similar to a user-given title using textual metadata and natural language processing techniques.

---

# 🔍 Project Overview:-
The recommendation model suggests movies by analyzing their content — such as genres, keywords, overviews, and cast — instead of user ratings. It uses **TF-IDF vectorization** to convert text data into numerical form and **cosine similarity** to compute the closeness between movies.

---

# 🛠️ Features:-
- 🎯 Suggests top similar movies based on content
- 🧠 Uses **TF-IDF Vectorizer** for text feature extraction
- 📏 Calculates similarity using **Cosine Similarity**
- 🚫 Handles invalid or misspelled movie names gracefully
- ✅ Cleaned and preprocessed data for better results

---

# 🧪 Technologies Used:-
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TF-IDF Vectorizer  
- Cosine Similarity  
- Google Colab (for execution)

---

## 🗃️ Dataset:-
The system uses a movie dataset (`movies.csv`) containing:
- Movie Title  
- Genres  
- Keywords  
- Overview  
- Cast  
- Index (unique ID)

> Ensure `movies.csv` is placed in the same directory as your notebook.

---

# ⚙️ How It Works:-
1. **Data Cleaning**: Handle missing values and convert text data to lowercase.
2. **Feature Engineering**: Combine important columns (overview, keywords, genres, cast) into a single feature.
3. **Text Vectorization**: Use **TF-IDF Vectorizer** to convert text into numeric vectors.
4. **Similarity Computation**: Use **Cosine Similarity** to compute distances between movie vectors.
5. **Recommendation**: For a given movie, return the top 10–30 most similar movies.

---

# 🚀 How to Run:-

1. Open the project in Google Colab or Jupyter Notebook.
2. Upload the `movies.csv` file.
3. Run all cells in order.
4. Input a movie name when prompted to get recommendations.

# 📚 Learning Outcome:-

- Understood how content-based filtering works
- Learned about text vectorization and cosine similarity
- Improved data preprocessing and error handling
- Applied ML tools in a practical project

---

# 🙋‍♂️ Project Developed By:-
**Pratyush Prasoon**  
B.Tech, Information Technology  
KIIT University  
Applied Programming Lab Project

---

# 📃 License:-
This project is for educational purposes only.

