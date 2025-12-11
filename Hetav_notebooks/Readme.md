CS171 Final Project — Soccer Match Outcome Prediction

This project builds machine learning models to predict soccer match outcomes (Win, Draw, Loss) using engineered features from the Soccer Match Event Dataset.
The workflow includes data preprocessing, model construction, evaluation, and visualization.

Notebooks Included
------------------

1. Data_Preprocessing.ipynb
   - Loads and cleans raw match-event data
   - Removes missing values and label leakage
   - Generates engineered features (efficiency, dominance, attack/defense metrics)
   - Saves the final match-level dataset for modeling

2. Random_Forest_Classifier.ipynb
   - Trains a Random Forest model using scikit-learn
   - Evaluates accuracy and provides a classification report
   - Includes confusion matrix and feature importance visualization

3. MLP_Model.ipynb
   - Builds a Multi-Layer Perceptron (MLP) model using PyTorch
   - Tracks training and validation loss across epochs
   - Plots training accuracy curves
   - Evaluates model performance with a confusion matrix

4. Analysis_and_Visualization.ipynb
   - Visualizes dataset patterns and model behavior
   - Compares predictions across machine learning models
   - Interprets results using plots and summary statistics

Technologies Used
-----------------
- Python
- PyTorch
- scikit-learn
- pandas, numpy
- matplotlib, seaborn

Project Goal
------------
The objective of this project is to determine which match-level features best predict soccer match outcomes and to compare how different machine learning models perform when trained on the same dataset.
