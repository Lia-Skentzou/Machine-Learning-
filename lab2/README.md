# ML Lab 2 — Hyperspectral Image Clustering and Dimensionality Reduction (NTUA, Fall 2023)

## Summary

This project focuses on the application of unsupervised learning techniques to hyperspectral image data. The task involved clustering pixels of a hyperspectral satellite image using the k-Means algorithm and evaluating performance relative to known ground truth labels. Additionally, dimensionality reduction using PCA was applied to explore its impact on clustering quality and computational efficiency.

The image used in this assignment is the Indian Pines dataset, commonly used in remote sensing and hyperspectral image classification tasks.

## Key Objectives

- Load and preprocess a hyperspectral image and corresponding ground truth labels.
- Explore the dataset through visualization and statistical analysis.
- Extract and compare spectral signatures of land-cover types.
- Apply k-Means clustering and evaluate the results using:
  - Accuracy (via label alignment)
  - Adjusted Rand Index
  - Silhouette Score
- Visualize confusion matrix and class-wise distribution.
- Perform dimensionality reduction using PCA.
- Analyze the relationship between the number of PCA components and clustering performance.

## Technologies Used

- Python 3.x
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Munkres (for label alignment)

## Key Concepts Applied

- Hyperspectral image processing
- Spectral signature analysis
- k-Means clustering
- Dimensionality reduction (PCA)
- Clustering performance metrics
- Confusion matrix visualization
