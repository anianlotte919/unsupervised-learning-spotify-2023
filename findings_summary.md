# Findings Summary

- **Clustering method:** K-Means on scaled acoustic + popularity features.
- **Model selection:** Silhouette identified k = <your_k>.
- **PCA (2D):** Clusters show separation along energy/danceability vs. acousticness/valence.
- **Profiles:** High-energy clusters align with dance/EDM; high-acousticness clusters align with relaxed/acoustic songs.
- **Limitations:** K-Means assumes spherical clusters; no text embeddings for genre/lyrics.
- **Future work:** Try GMM/HDBSCAN; add text/temporal features; analyze multiple years.
