# Eigenfaces Face Recognition System

A Java-based facial recognition system implementing the Eigenfaces method using Principal Component Analysis (PCA).  
Developed as part of coursework in Informatics Engineering, achieving a final grade of 19/20.

This project includes:
- Mean face computation
- Construction of A and AᵀA matrices
- Eigenvalue and eigenvector extraction
- Eigenfaces generation
- Dimensionality reduction
- Face reconstruction
- Identification using Euclidean distance
- CSV import/export
- Interactive and command-line modes

## Features

### PCA Pipeline
- Computes the mean image
- Builds the difference matrix
- Computes the covariance matrix
- Extracts eigenvalues and eigenvectors
- Normalizes eigenvectors to produce eigenfaces

### Face Reconstruction
- Reconstructs faces using a configurable number of principal components
- Demonstrates compression and noise reduction

### Recognition System
- Projects images into eigenface space
- Computes feature vectors
- Determines closest match through Euclidean distance

### Input & Output
- Handles image matrices in CSV format
- Exports processed matrices
- Saves reconstructed faces as JPEG
- Supports CLI and interactive execution

## Technologies Used

- Java
- Apache Commons Math
- BufferedImage API
- CSV Processing
- Linear Algebra (PCA, Eigenfaces)
- File I/O


## Example Outputs

- Mean face
- Eigenfaces
- Reconstructed images
- CSV matrices
- Distance metrics

## Theory Summary (Eigenfaces)

Steps:
1. Convert images into vectors
2. Compute the mean face
3. Subtract the mean (A matrix)
4. Compute the covariance matrix
5. Extract eigenvalues and eigenvectors
6. Select the top principal components
7. Project new images into eigenface space
8. Compare using Euclidean distance

## Credits

Project developed collaboratively by:

- [André Pinho](https://github.com/AndreSiPinho)
- [Carlota Lemos](https://github.com/carlotalemos)
- [Eduardo Almeida](https://github.com/EduardoAlmeida-1241418)
- [Mara Santos](https://github.com/1241452)

## Final Grade

19/20
