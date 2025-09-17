# 🎬 Movie Recommendation System  

[![Status](https://img.shields.io/badge/Project-Completed-green)]()  
[![Python](https://img.shields.io/badge/Made%20With-Python%203.9%2B-blue)]()  
[![Libraries](https://img.shields.io/badge/Libraries-Numpy%20%7C%20Pandas%20%7C%20ScikitLearn-orange)]()  
[![Algorithm](https://img.shields.io/badge/Algorithm-Content--Based%20Filtering-red)]()  

An intelligent **Movie Recommendation System** built in **Google Colab** using **content-based filtering**.  
It suggests similar movies to a user’s favorite by analyzing genres, keywords, tagline, cast, and director from a dataset.  

---

## 📖 Overview  

This project demonstrates a **Content-Based Recommendation Engine** for movies.  
The system uses **TF-IDF Vectorization** and **Cosine Similarity** to find relationships between movies and provide personalized recommendations.  

- Input: A movie name (typed by the user).  
- Output: A ranked list of movies similar in content.  

---

## ✨ Features  

- 🔍 **Content-Based Filtering**: No user history required — recommendations are based solely on movie attributes.  
- 🧩 **Feature Engineering**: Combines `genres`, `keywords`, `tagline`, `cast`, and `director`.  
- 🧮 **TF-IDF Vectorization**: Converts text features into numerical vectors.  
- 📐 **Cosine Similarity**: Measures closeness between movies.  
- 🎯 **Close Match Handling**: Uses fuzzy matching (`difflib`) to accept similar user inputs.  
- 📊 **Top-N Recommendations**: Suggests up to 30 similar movies.  

---


---

## 🛠️ Technologies Used  

- **Python**  
- **NumPy**  
- **Pandas**  
- **Scikit-Learn** (`TfidfVectorizer`, `cosine_similarity`)  
- **Difflib** (for fuzzy matching)  
- **Google Colab** (execution environment)  

---

## 📂 Dataset  

The dataset (`movies.csv`) contains metadata for movies, including:  

- Title  
- Genres  
- Keywords  
- Tagline  
- Cast  
- Director  

⚠️ *Make sure your dataset includes these fields to run the project successfully.*  

---

## 🚀 Usage  

1. Clone the repository / open the notebook in **Google Colab**.  
2. Upload the dataset (`movies.csv`).  
3. Run the notebook cells.  
4. Enter your favorite movie when prompted:  

```bash
Enter your favourite movie name : Avatar


