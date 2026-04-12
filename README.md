# ML-OEP-26

Face recognition using Principal Component Analysis (PCA) and machine learning to build a face recognition system.

## What I Did In This Project

1. Prepared the AT&T face dataset by organizing images subject-wise and splitting them into training and testing sets.
2. Built a PCA-based face representation pipeline by computing the mean face, extracting eigenfaces, and projecting images into a lower-dimensional face space.
3. Analyzed how much information the PCA components preserve using cumulative explained variance.
4. Reconstructed both training and unseen test images with different numbers of principal components to study reconstruction quality and error trends.
5. Converted all face images into eigen-space feature vectors so they could be used for recognition tasks.
6. Implemented a nearest-neighbor face recognition baseline in PCA space and evaluated how accuracy changes with the number of retained dimensions.
7. Trained and compared an SVM classifier on the same PCA features to measure whether it performs better than the nearest-neighbor approach.
8. Extended the system to open-set recognition by adding threshold-based rejection for non-face inputs and unknown persons.

## Project Outcome

This project shows how PCA can be used not only for dimensionality reduction, but also for face reconstruction, feature extraction, closed-set recognition, classifier comparison, and open-set face recognition.
