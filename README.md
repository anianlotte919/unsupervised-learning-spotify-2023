# Unsupervised Learning on Spotify’s 2023 Most-Streamed Songs

**Author:** Yun Xia  
**Course:** Unsupervised Algorithms in Machine Learning — Deliverable 3

## Goal
Discover hidden structure among 2023 Spotify hits using **K-Means** on acoustic and platform-popularity features, and visualize clusters with **PCA**.

## Repository Contents
- `notebooks/deliverable1_kaggle.ipynb` — full analysis notebook (Deliverable 1)
- `figures/` — exported figures used in the report
- `reports/findings_summary.md` — short written summary
- `environment.yml` — minimal environment to reproduce plots
- `data/README.md` — dataset source and access instructions

## Dataset
Kaggle dataset: **Top Spotify Songs 2023**.  
Data is **not** redistributed here. To reproduce:
1. Create a Kaggle API token and accept dataset terms.
2. In a Kaggle notebook, add the dataset **“top-spotify-songs-2023”**.
3. Run `notebooks/deliverable1_kaggle.ipynb`.

## Methods
1. Data overview & missingness check  
2. EDA (top artists/tracks, numeric distributions, **correlation heatmaps**)  
3. **K-Means** with scaling; model selection via **Elbow** and **Silhouette**  
4. **PCA (2D)** for cluster visualization  
5. Cluster profiling (mean features per cluster)

## Key Results (Figures)
- Correlation heatmap → `figures/correlation_heatmap.png`  
- Silhouette vs. k → `figures/silhouette_vs_k.png`  
- PCA cluster scatter → `figures/pca_clusters.png`  
- Cluster profile heatmap → `figures/cluster_profiles_heatmap.png`

## How to Reproduce Locally

### clone this repository
git clone https://github.com/anianlotte919/unsupervised-learning-spotify-2023.git
cd unsupervised-learning-spotify-2023

### install dependencies
pip install -r requirements.txt

### open the notebook
jupyter lab notebooks/unsupervised-learning-final-project.ipynb



## Citation

If you refer to this repository, please cite it as:

Yun Xia. *Unsupervised Learning on Spotify’s 2023 Most-Streamed Songs*. 2025.  
GitHub: https://github.com/anianlotte919/unsupervised-learning-spotify-2023
