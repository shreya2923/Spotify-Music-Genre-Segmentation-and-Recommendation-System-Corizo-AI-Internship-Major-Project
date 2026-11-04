# Spotify Song Genre Segmentation and Cluster-Aware Recommendation System

## Project Overview

This major project focuses on developing an automated Spotify song genre segmentation and music recommendation system using machine learning techniques. The system analyzes Spotify audio features to identify six distinct acoustic behavior clusters and uses these clusters to generate personalized, content-based music recommendations.

The project involves data preprocessing, exploratory data analysis, data visualization, correlation analysis, feature engineering, K-Means clustering, cluster interpretation, and cosine-similarity-based recommendation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Principal Component Analysis (PCA)
- Cosine Similarity
- Streamlit
- Joblib
- Google Colab

## Machine Learning Techniques

- K-Means Clustering for song segmentation.
- Standardization of audio features.
- Principal Component Analysis (PCA) for cluster visualization.
- Cosine Similarity for content-based music recommendations.

## Key Features

- Spotify dataset preprocessing and data cleaning.
- Exploratory Data Analysis (EDA) and audio-feature visualization.
- Correlation matrix analysis.
- Feature analysis and acoustic behavior identification.
- Segmentation of songs into six acoustic clusters using K-Means.
- Cluster profiling and interpretation.
- Playlist genre and playlist name analysis.
- Cluster-aware music recommendation using cosine similarity.
- External testing and recommendation evaluation.
- Model serialization for reuse.
- Interactive music recommendation interface using Streamlit.

## Project Workflow

1. Dataset Collection and Loading
2. Data Preprocessing and Cleaning
3. Exploratory Data Analysis
4. Audio Feature Analysis and Visualization
5. Correlation Matrix Analysis
6. Feature Standardization
7. K-Means Clustering
8. Cluster Visualization and Interpretation
9. Playlist Genre and Name Analysis
10. Content-Based Music Recommendation
11. External Testing and Validation
12. Streamlit Application Deployment

## Recommendation Approach

The system follows a cluster-aware content-based recommendation approach.

- Identifies the acoustic cluster of the selected song.
- Filters candidate songs belonging to the same cluster.
- Calculates cosine similarity using standardized audio features.
- Ranks similar songs based on similarity scores.
- Presents relevant music recommendations through an interactive interface.

## Project Links

- **Google Colab:** [Open Spotify Music Genre Segmentation Notebook](https://colab.research.google.com/drive/13uvyaamWAo2FtBvbJl65CxFPdMy2VsUl)

- **Google Drive:** [View Project Files](https://drive.google.com/drive/folders/1H7yy-K7YEfw9B22XZ6mB_xURoKTTmttr?usp=sharing)

- **GitHub:** [View Source Code](https://github.com/shreya2923/Spotify-Music-Genre-Segmentation-and-Recommendation-System-Corizo-AI-Internship-Major-Project)
