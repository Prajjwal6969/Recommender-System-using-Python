# 🎯 Recommender Systems Collection

This repository contains two mini-projects built using Python and machine learning for content-based recommendation:

- 🎵 **Song Recommender System**
- 🎬 **Movie Recommender System**

Both projects demonstrate how similarity metrics and feature engineering can be used to recommend relevant items to users.

---

## 🔍 Project 1: Song Recommender System

### 📌 Description:
This project recommends songs based on audio features using **content-based filtering**. It analyzes attributes like danceability, energy, tempo, valence, etc., and uses similarity metrics to suggest songs that sound similar.

### 🧠 Methodology:
- Features Used:
  - Danceability
  - Energy
  - Valence
  - Tempo
  - Acousticness
  - Liveness
- Techniques:
  - Cosine Similarity or K-Nearest Neighbors
  - Feature scaling and preprocessing

### ✅ Output:
Given a song name, it returns a list of similar songs based on their audio characteristics.

---

## 🎥 Project 2: Movie Recommender System

### 📌 Description:
This system recommends movies based on genres, cast, director, and keywords using **content-based filtering**. The project builds a "tag" feature by combining various metadata.

### 🧠 Techniques Used:
- Text preprocessing and vectorization using `CountVectorizer` or `TfidfVectorizer`
- Cosine Similarity to calculate similarity between movies
- Metadata parsing (cast, crew, overview, genres)

### 🛠️ Input:
- User provides a movie name.

### 🎯 Output:
- Returns top 5–10 similar movies.

---

## 📁 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Prajjwal6969/recommender-systems.git
   cd recommender-systems
2. Install required libraries:
    pip install -r requirements.txt
   
4. Launch the Jupyter notebooks:
    jupyter notebook

