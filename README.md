# Iris LDA Classification
This repository contains the implementation of Linear Discriminant Analysis (LDA) for classification of Iris flower species based on their measurements. The project demonstrates the use of LDA for dimensionality reduction and classification.
## Overview
The Iris dataset is a classic dataset used in machine learning and statistics. It contains 150 samples of iris flowers from three different species: Iris Setosa, Iris Versicolor, and Iris Virginica. Each sample includes four features: sepal length, sepal width, petal length, and petal width. The goal is to build a classifier that can predict the species of an iris flower based on these four measurements.
## Dependencies
- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn
## Getting Started
1. Clone this repository to your local machine.
2. Install the required dependencies using pip: pip install -r requirements.txt
3. Run the main script: python iris_lda_classification.py
## Project Structure
- iris_lda_classification.py: Main script for loading the dataset, applying LDA, and evaluating the classification performance.
- requirements.txt: Contains the required dependencies for this project.
## LDA for Dimensionality Reduction
Linear Discriminant Analysis (LDA) is used as a dimensionality reduction technique, transforming the four-dimensional feature space into a lower-dimensional space. In this case, the transformed space has two dimensions, which helps visualize the data and reduces the computational complexity of the model.
## Model Evaluation
The LDA classifier's performance is evaluated using accuracy, precision, recall, and F1-score metrics. A confusion matrix is also generated to visualize the performance of the classifier.
## Results
The LDA classifier demonstrates high accuracy in predicting the species of iris flowers based on their measurements. The results, along with the reduced-dimensionality data visualization, are displayed in the form of plots.
