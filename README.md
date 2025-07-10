# 🎧 Spotify Song Clustering for Recommendation Systems

This project uses unsupervised machine learning to cluster songs by The Rolling Stones using audio features from Spotify’s API. The goal is to simulate how a music streaming platform like Spotify might enhance its recommendation system by grouping similar songs into cohorts.

---

## 📌 Project Objective

Customers expect personalized content — whether on Netflix, Spotify, or other platforms. This project explores how clustering techniques can help music platforms group songs with similar characteristics to provide more relevant recommendations.

---

## 🧰 Tools & Technologies

- **Python**
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `scikit-learn` for clustering (K-Means)
- **Spotify API** (dataset pre-extracted)
- **Jupyter Notebook**

---

## 📊 Features Used

Each song includes various musical attributes provided by Spotify’s API, such as:

- Danceability  
- Energy  
- Acousticness  
- Instrumentalness  
- Liveness  
- Speechiness  
- Tempo  
- Valence

---

## 🔍 Process Overview

1. **Data Cleaning & Exploration**
   - Removed duplicates and irrelevant features
   - Visualized feature distributions and correlations

2. **Feature Scaling & Dimensionality Reduction**
   - Standardized features
   - Applied PCA for 2D visualization of clusters

3. **Clustering**
   - Used K-Means clustering to group songs
   - Tested multiple `k` values and used the elbow method to determine optimal clusters

4. **Visualization**
   - Plotted clusters using PCA-reduced components
   - Analyzed characteristics of each cluster to understand grouping logic

---

## ✅ Key Outcomes

- Successfully grouped Rolling Stones songs into meaningful clusters based on musical features
- Demonstrated how content-based filtering techniques can improve personalization in music platforms
- Practiced core skills in data science, including EDA, clustering, and model evaluation

---

## 📁 Files

- `spotify_rolling_stones_clustering.ipynb` – Main notebook with code and visualizations
- `rolling_stones_spotify.csv` – Dataset with extracted audio features (if included)
- `README.md` – This file

---

## 📎 Future Improvements

- Integrate live Spotify API calls to update data in real time  
- Expand dataset to include songs across multiple artists and genres  
- Explore other clustering methods (e.g., DBSCAN, Hierarchical)

---

## 👨‍💻 Author

**Elliot Halpern**  
Feel free to connect or reach out: [eshalp12@gmail.com](mailto:eshalp12@gmail.com)  
[GitHub Profile](https://github.com/yourusername) ← Replace this with your actual profile link

