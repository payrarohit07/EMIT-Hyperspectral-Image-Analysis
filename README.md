# Exploratory Analysis and Unsupervised Clustering of EMIT Hyperspectral Data

**Hyperspectral Remote Sensing | Spectral Analysis | PCA | t-SNE | K-means Clustering | Python**

## Project Overview

This project focuses on the exploratory analysis of hyperspectral satellite data acquired by NASA's Earth Surface Mineral Dust Source Investigation (EMIT) mission.

Using Python, the EMIT hyperspectral data were processed and analysed to investigate the spectral characteristics and spatial variations of pixels across a selected study area.

The analysis involves spectral signature visualisation, band-to-band correlation analysis, Principal Component Analysis (PCA), t-distributed Stochastic Neighbor Embedding (t-SNE), and K-means clustering.

The primary objective is to explore spectral similarities among pixels, reduce the dimensionality of the hyperspectral dataset, and investigate the resulting clusters through spatial visualisation and spectral analysis.

## Objectives

- Explore and understand NASA EMIT hyperspectral data.
- Examine pixel-wise spectral signatures across different wavelengths.
- Investigate correlations and redundancy among spectral bands.
- Apply PCA for dimensionality reduction and visualisation.
- Use t-SNE to explore similarities among pixels in a lower-dimensional feature space.
- Apply K-means clustering to group pixels based on their t-SNE representations.
- Analyse the spatial distribution and mean spectral characteristics of the resulting clusters.

  

## Dataset Information

The hyperspectral data used in this project were acquired by NASA's Earth Surface Mineral Dust Source Investigation (EMIT) mission.

- **Scene date:** 2 May 2024
- **Kaggle dataset:** EMIT_60233
- **Data product:** EMIT L2A Estimated Surface Reflectance and Uncertainty and Masks (60 m, V001)
- **Data format:** NetCDF

### Data Source

Green, R. (2022). *EMIT L2A Estimated Surface Reflectance and Uncertainty and Masks 60 m V001*. NASA EOSDIS LP DAAC.

[https://doi.org/10.5067/EMIT/EMITL2ARFL.001](https://doi.org/10.5067/EMIT/EMITL2ARFL.001)

### Accessing the Dataset

The dataset is available through Kaggle. No separate NASA Earthdata account is required to access the Kaggle copy.

To use the dataset in Kaggle:

1. Open the notebook editor.
2. Click **Add Input**.
3. Search for `EMIT_60233`.
4. Add the dataset to your notebook.
