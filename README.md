# PCA

Working directly with high-dimensional data, such as images, comes with A 640 × 480 pixel
color

For example image is a data point in a million-dimensional space, where every
pixel responds to three dimensions,one for each colorchannel (red, green,blue).

 difficulties of such data:
*  It is hard to analyze, interpretation is difficult, visualiza-
tion is nearly impossible.

* storage of the data vectors can be expensive.

high-dimensional data have many dimensions that are redundant and can be ex-
plained by a combination of other dimensions. Furthermore, dimensions
in high-dimensional data are often correlated so that the data possesses an
intrinsic lower-dimensional structure.

Dimensionality reduction exploits structure and correlation and allows us to work with a more compact rep-
resentation of the data, ideally without losing information. We can think
of dimensionality reduction as a compression technique, similar to jpeg or
mp3, which are compression algorithms for images and music.

**HOW TO DO A PCA?**

1. Standardize the range of continuous initial variables

2. Compute the covariance matrix to identify correlations

3. Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components

4. Create a feature vector to decide which principal components to keep

5. Recast the data along the principal components axes




In this repoaitory we will see various procedures involved IN PCA 
