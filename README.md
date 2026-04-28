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

- `exoplanet_clustering.ipynb` : full notebook
- `data/` : cleaned dataset
- `figures/` : plots used in report
- `report.pdf` : final report

## Dataset Source

NASA Exoplanet Archive:
https://exoplanetarchive.ipac.caltech.edu/

## Author

Your Name
University of Michigan
