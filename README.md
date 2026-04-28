# NASA-Exoplanet-Machine-Learning
Astro416finalproject
# Exoplanet Clustering using Machine Learning

## Project Overview

This project applies unsupervised machine learning methods to classify confirmed exoplanets into physically meaningful groups.

Using data from the NASA Exoplanet Archive, planets are clustered based on radius, mass, orbital properties, and host star characteristics.

## Methods Used

- KMeans Clustering
- Silhouette Score Evaluation
- PCA Visualization
- Random Forest Feature Importance

## Key Results

- k=2 gives the strongest large-scale separation between rocky planets and gas giants.
- k=5 provides a more detailed taxonomy including mini-Neptunes, dense rocky planets, and inflated gas giants.
- Planet radius and planet mass are the most important clustering features.

## Files

- `exoplanet_clustering_finalversion.ipynb` : final version notebook
- `exoplanet_clustering_initialversion.ipynb` : initial version notebook
- `PS_2026.04.27_17.30.53.csv` : cleaned dataset used for final version
- `PS_2026.04.01_18.53.37.csv` : cleaned dataset used for initial version


## Dataset Source

NASA Exoplanet Archive:
https://exoplanetarchive.ipac.caltech.edu/
