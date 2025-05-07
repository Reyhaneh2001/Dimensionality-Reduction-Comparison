# Dimensionality Reduction Algorithms Comparison

##  Overview

This project compares **8 different dimensionality reduction algorithms** implemented in scikit-learn and visualizes their results on the famous **Digits dataset**. The aim of this comparison is to understand the differences in the algorithms' ability to reduce data to 2D while maintaining various aspects of the original structure, such as variance, class separability, and distance relationships.

##  Algorithms Compared

The following dimensionality reduction techniques are explored:

1. **PCA (Principal Component Analysis)**: A linear method that reduces dimensionality by maximizing variance.
2. **t-SNE (t-distributed Stochastic Neighbor Embedding)**: A nonlinear technique that focuses on preserving local neighborhood structure.
3. **UMAP (Uniform Manifold Approximation and Projection)**: A faster nonlinear method that preserves both local and global structure.
4. **LDA (Linear Discriminant Analysis)**: A supervised method that maximizes class separability.
5. **Isomap**: A nonlinear technique that preserves geodesic distances along the data manifold.
6. **MDS (Multidimensional Scaling)**: A distance-preserving method that focuses on pairwise distances between points.
7. **Kernel PCA**: A nonlinear extension of PCA that uses kernel functions to capture complex structures.
8. **Truncated SVD**: A linear dimensionality reduction technique that is often used in Natural Language Processing (NLP) with sparse matrices.

##  Dataset

The **Digits dataset** from scikit-learn is used for this comparison. It consists of 8x8 pixel grayscale images of handwritten digits (0-9), providing a good balance of complexity and interpretability for dimensionality reduction techniques.

- **Total Instances**: 1,797
- **Features**: 64 (8x8 pixel images)
- **Classes**: 10 (digits 0-9)
