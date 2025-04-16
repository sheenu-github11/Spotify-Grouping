# 🎧 Spotify Genre Grouping Analysis

This repository presents an analysis of Spotify audio data with a focus on grouping tracks by their genre based on musical features using clustering and visualization techniques.

---

## 🎵 Project Overview

Spotify provides rich audio features for millions of songs through its Web API. This project explores a subset of that data and aims to:

- Analyze and visualize relationships between audio features
- Apply clustering algorithms to group songs by genre
- Understand genre patterns and music characteristics through unsupervised learning
- Provide intuitive visualizations of clusters and audio traits

---

## 🧪 Dataset Description

The dataset used contains various audio features of Spotify tracks across genres like rock, hip-hop, classical, EDM, and more.

Key features include:

- Danceability  
- Energy  
- Loudness  
- Speechiness  
- Acousticness  
- Instrumentalness  
- Liveness  
- Valence  
- Tempo  
- Duration  
- Genre  

The data was preprocessed and cleaned to ensure meaningful analysis and visualization.

---

## 🛠️ Technologies Used

- Python 🐍  
- Jupyter Notebook 📓  
- Pandas & NumPy 🔢  
- Scikit-learn 🤖  
- Plotly 📊  
- Seaborn & Matplotlib 📉  
- PCA and K-Means clustering

---


## 📌 Key Insights

- **Clustering Reveals Genres**: Unsupervised clustering successfully grouped songs with similar audio features, often aligning with known genres.
- **Feature Importance**: Features like energy, danceability, and tempo were highly influential in separating musical styles.
- **Dimensionality Reduction**: PCA reduced data to 2D for visualization without losing essential patterns.

---

## 🧠 Future Work

- Add deep learning-based genre classification  
- Expand dataset with more tracks and live updates via Spotify API  
- Add interactive dashboard using Streamlit or Dash  

---

## 📚 References

- Spotify Web API  
- [Kaggle Datasets](https://www.kaggle.com/datasets)  
- Audio Feature Definitions from Spotify Developer Docs

---
