# Findings Summary

- **Clustering method:** K-Means applied to standardized acoustic and popularity features.  
- **Model selection:** The silhouette analysis identified **k = 4** as the optimal number of clusters.  
- **PCA (2D):** The first two principal components capture variation mainly in **energy, danceability**, and **valence**, separating energetic/dance tracks from relaxed/acoustic ones.  
- **Cluster profiles:**  
  - High-energy clusters correspond to mainstream pop and dance/EDM tracks.  
  - High-acousticness clusters include calmer, emotional, or acoustic songs.  
- **Limitations:** K-Means assumes spherical clusters and does not account for lyrics, genre labels, or temporal factors.  
- **Future work:** Explore **GMM** or **HDBSCAN** for flexible cluster boundaries; integrate **text and time-based features** to analyze multi-year music trends.
