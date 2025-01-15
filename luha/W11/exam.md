# Exam

## Outline for Presentation on Basis, PCA, and Generative Models

1. Introduction (30 seconds)
    * Introduce the key concepts of basis, transformations, dimensionality reduction, and generative models.
    * Highlight the focus areas:
        * (a) Basis and transformations.
        * (b) Dimensionality reduction and PCA, focusing on Mandatory Assignment 2.
        * (c) Generative models and PCA.
        * (d) Eigenvalues, covariance matrix, and basis.
2. Basis and Transformations (1 minute)
    * Definition of Basis:
        * Explain how a basis defines the coordinate system in a vector space.
        * Discuss the role of basis in transformations (e.g., rotations, scaling).
    * Applications:
        * Highlight how transformations like PCA change the basis to align with data variance.
3. Dimensionality Reduction and PCA (1.5 minutes)
    * Purpose of PCA:
        * Introduce PCA as a technique to reduce dimensionality while retaining significant variance.
    * Steps in PCA:
        * Centering data, calculating covariance matrix, finding eigenvalues/eigenvectors, projecting data.
    * Mandatory Assignment 2:
        * Use examples from 01-pca_intro.ipynb to demonstrate:
            * How PCA reduces dimensions.
            * Visualizations of principal components and reduced data representation.
4. Generative Models and PCA (1.5 minutes)
    * Generative Models:
        * Define generative models and their goal of learning data distributions.
    * Relation to PCA:
        * Explain how PCA aids generative models by reducing complexity while maintaining key data patterns.
    * Mandatory Assignment 2:
        * Use 02-shape_generation.ipynb to illustrate:
            * How PCA-derived principal components are used to generate new shapes or data points.
            * Examples of shape reconstruction using a subset of principal components.
5. Eigenvalues, Covariance Matrix, and Basis (1.5 minutes)
    * Covariance Matrix:
        * Explain its role in identifying data variance and correlation between features.
    * Eigenvalues and Eigenvectors:
        * Define eigenvalues as indicators of variance and eigenvectors as new basis directions.
    * Applications in PCA:
        * Discuss how PCA leverages the covariance matrix to determine the principal components.
        * Show practical examples from 01-pca_intro.ipynb where eigenvalues guide dimensionality reduction.
6. Conclusion (30 seconds)
    * Recap the key takeaways:
        * Basis transformations and PCA are foundational for reducing dimensionality.
        * Generative models can utilize PCA to reconstruct or generate data efficiently.
        * Eigenvalues and the covariance matrix provide critical insights into data variance and structure.
    * Emphasize how Mandatory Assignment 2 demonstrates these concepts in practical settings.

## Notes

The model can benefit to train on a data set which has had it dimensions reduced by PCA due to reduced complexity and hopefully less noise.
