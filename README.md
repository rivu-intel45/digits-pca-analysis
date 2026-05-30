# PCA Calculation on Digits Dataset

An interactive Jupyter Notebook project that applies **Principal Component Analysis (PCA)** on a handwritten digits dataset to reduce dimensionality and visualize high-dimensional pixel data.

---

## Project Overview

This project walks through a basic PCA workflow:

- Loading and exploring the digits dataset
- Separating pixel features from the target digit labels
- Visualizing a single digit image using Matplotlib and Seaborn
- Standardizing pixel values using `StandardScaler`
- Applying PCA for dimensionality reduction
- Visualizing digit clusters in 2D and 3D PCA space
- Understanding explained variance from principal components

---

## Dataset

The project uses a CSV file named:

```text
digits.csv
```
The dataset contains handwritten digit image data where:

- Each row represents one digit image
- Pixel columns represent the intensity values of the image
-`number_label` represents the actual digit class
