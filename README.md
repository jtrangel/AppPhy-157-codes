# AppPhy-157-codes
Undergrad 3rd yr 2nd sem

This semester the outputs were divided into three main parts (A,B,C) which had a focus on different topics per part:

* A - Complex systems
* B - Image processing
* C - Machine Learning

Tech stack:
* [Python](https://www.python.org/)
* [Google Colab](https://colab.research.google.com/)
* [Jupyter Notebook](https://jupyter.org/)
* [Anaconda](https://www.anaconda.com/)

## 157A

* Report 1 -  Monte carlo simulations and random walks. Interesting phenomena such as Brownian motion was also observed
* Report 2 - Cellular automata and agent based modelling (Sugarscape model)
* Report 3 - Networks (Graph topology, Nodes, Edges) along with applications such as network density, clustering, node importance and relationships.

## 157B

Consists of 2 `.ipynb` files, which covered results and data for three reports on image processing techniques in python

### 157B1

Covered the creation of 3d shapes, apertures, graphs, and visualizing their 2d and 3d outputs. Includes also image processing (greyscale upscaling, RGB image filter algorithms, etc.)

### 157B2

Use of Fourier transforms for simulating diffraction patterns, image convolution, and feature matching. Mainly covers the use of the Fast Fourier Transform which is extensively optimized via matrix decomposition and removal of redundant calculations.

## 157C (Modules 1 to 3)

### Module 1

Demonstrates how to use cross-validation to avoid overfitting in a regression model. Uses the common modelling practice of splitting data set into training, cross-validation, and test sets. From here wte fit a polynomial regression model to the training set for different polynomial degrees. We can then compare how the model does for each polynomial degree of fit. This is done using RMSE (Root Mean Square Error) values.

### Module 2 

Tackles classification using the Sloan Digital Sky Survey (SDSS) dataset. The data is that of morphoogical galaxies, where each galaxy can be classified based on their shape (spiral, merger, elliptical). The dataset includes 16 features which are then used to predict the shape which is the target. We use a decision tree classifier and evaluate the results using a confusion matrix, which highlights the performance of the classifier for the given parameters.

### Module 3

Covers the usage of dimensionality reduction to identify the most important features in a dataset. Specifically I do Principal Component Analysis (PCA) on galaxy spectra data from the Sloan Digital Sky Survey (SDSS) dataset. In this case, PCA is used to reduce the number of features from 1000 to 4. The results show that the first 4 principal components account for 85% of the variance in the data. This means that the original 1000 features can be effectively summarized using just 4 numbers/columns.

