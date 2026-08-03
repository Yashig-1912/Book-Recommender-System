# 📚 Book Recommender System

A content-filtering and collaborative-filtering machine learning project that recommends books based on user ratings. Built using Python, Pandas, Scikit-Learn, and Google Cloud Storage.

---

## 🚀 Features
* **Collaborative Filtering:** Uses Nearest Neighbors algorithm to find patterns in user ratings.
* **Large-Scale Data Handling:** Processes datasets containing hundreds of thousands of users and books, and over 1 million ratings hosted securely on Google Cloud Storage.
* **Interactive UI:** Includes an interactive input widget directly within the notebook so users can type a book title and instantly get 5 recommendations.

---

## 📊 Dataset Overview
The model is trained on a filtered subset of data:
* **Books:** ~271,000 entries
* **Users:** ~278,000 entries
* **Ratings:** ~1.14 million entries (filtered for users with >200 ratings and books with >50 ratings)

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Ipywidgets
* **Cloud Storage:** Google Cloud Platform (GCP)
* **Environment:** Google Colab 

---

## 🖥️ How to Use the Interactive Widget
If you are viewing this notebook on GitHub or Google Colab:
1. Run all preceding data-loading and model-training cells.
2. Locate the **Interactive Book Recommender** widget cell near the top/middle of the notebook.
3. Type a book title into the text box and click **Get Recommendations** to see 5 similar book suggestions instantly!
