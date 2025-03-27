# Linear Algebra Project

This project contains two Jupyter notebooks that explore different topics in machine learning and image processing. Below is a brief description of each notebook.

## 1. Spectral Clustering on Graphs

This notebook implements **Spectral Clustering**, a technique for partitioning data into clusters. Spectral clustering is particularly useful for non-linearly separable data and complex feature spaces. The method constructs a graph from the dataset and then uses its spectral properties (such as eigenvalues and eigenvectors of the graph Laplacian) to identify meaningful clusters.

### Topics Covered:
- Introduction to spectral clustering
- Implementation of spectral clustering
- Evaluating the model using different datasets

---

## 2. Image Processing and Denoising with FFT and SVD

This notebook explores **image processing** and **denoising** techniques using **Fast Fourier Transform (FFT)** and **Singular Value Decomposition (SVD)**. FFT is used to analyze the frequency components of an image, while SVD is applied for compression and noise reduction.

### Topics Covered:
- Introduction to FFT and SVD in image processing
- Using FFT for frequency analysis of images
- Applying SVD for image compression and noise reduction
- Implementation and comparison of results before and after denoising

---

## Prerequisites

To run the notebooks, install the following dependencies:

```bash
pip install numpy scipy matplotlib scikit-learn opencv-python
