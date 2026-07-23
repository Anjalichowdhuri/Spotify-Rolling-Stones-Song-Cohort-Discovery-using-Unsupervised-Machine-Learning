# Spotify-Rolling-Stones-Song-Cohort-Discovery-using-Unsupervised-Machine-Learning
A machine learning project that discovers hidden song cohorts in the Rolling Stones' Spotify catalog using K-Means, Hierarchical Clustering, DBSCAN, Gaussian Mixture Models, PCA, and t-SNE.

# Overview
This project explores the audio characteristics of songs from the Rolling Stones' Spotify catalog using unsupervised machine learning techniques. The objective is to discover natural groupings of songs based on their musical attributes and identify meaningful patterns without predefined labels.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, dimensionality reduction, and cluster evaluation to gain insights into different song cohorts.

---

# Objectives

- Analyze Spotify audio features of Rolling Stones songs.
- Perform exploratory data analysis to understand the dataset.
- Discover hidden song clusters using multiple clustering algorithms.
- Compare clustering performance using evaluation metrics.
- Visualize high-dimensional data using dimensionality reduction techniques.

---

# Dataset

The dataset contains Spotify audio features for Rolling Stones songs, including attributes such as:

- Danceability
- Energy
- Acousticness
- Instrumentalness
- Speechiness
- Liveness
- Valence
- Tempo
- Popularity
- Duration
- Release Date

---

# Project Workflow

```
Spotify Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Feature Scaling
        │
        ▼
Clustering Algorithms
        │
        ├── K-Means
        ├── Hierarchical Clustering
        ├── DBSCAN
        └── Gaussian Mixture Model
        │
        ▼
Model Evaluation
        │
        ▼
PCA & t-SNE Visualization
        │
        ▼
Cluster Interpretation
```

---

# Techniques Used

# Data Preprocessing

- Handling missing values
- Removing duplicate records
- Feature selection
- Data normalization using StandardScaler

# Exploratory Data Analysis (EDA)

- Distribution analysis
- Correlation analysis
- Feature visualization
- Statistical summaries

# Machine Learning Algorithms

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Model (GMM)

# Dimensionality Reduction

- Principal Component Analysis (PCA)
- t-Distributed Stochastic Neighbor Embedding (t-SNE)

# Cluster Evaluation

- Elbow Method
- Silhouette Score

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Repository Structure

```
├── spotify_ml_project.ipynb
├── dataset/
├── images/
└── README.md
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/spotify-song-cohort-discovery.git
```

Navigate to the project directory:

```bash
cd spotify-song-cohort-discovery
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
spotify_ml_project.ipynb
```

---

# Results

The project identifies distinct song cohorts by comparing multiple clustering algorithms and visualizes the resulting clusters using PCA and t-SNE. These clusters provide insights into similarities in musical characteristics such as energy, danceability, tempo, and acousticness.

---

# Future Improvements

- Apply deep learning-based embedding techniques.
- Include songs from multiple artists for comparative analysis.
- Build an interactive dashboard for cluster exploration.
- Deploy the analysis as a web application.

---

# Author
*Anjali Chowdhury*
