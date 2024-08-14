# Music-Genre-Classification
This repository contains a machine learning project for classifying music tracks into genres using models like KNN, Gaussian Naive Bayes, and Logistic Regression. It includes data preprocessing, model training, and evaluation, ideal for music recommendation and playlist generation.

# Music Genre Classification
Overview
This project focuses on classifying music tracks into various genres using machine learning models. By analyzing audio features, we aim to automate the genre classification process, which is crucial for applications like music recommendation systems, playlist generation, and genre-specific radio stations.

# Data
The dataset comprises various audio features extracted from music tracks, such as tempo, loudness, and key, along with genre labels. Preprocessing involved removing unnecessary columns, handling null values, and encoding categorical variables to prepare the data for model training.

# Models
Three models were trained and evaluated:

# K-Nearest Neighbors (KNN): 
A model that classifies tracks based on the similarity of audio features.
# Gaussian Naive Bayes (GNB): 
A probabilistic model that assumes feature independence and performed best on this dataset.
# Logistic Regression (LR): 
A linear model that predicts the probability of a track belonging to a specific genre.

# Evaluation
The models were assessed using accuracy and F1 score:

Gaussian Naive Bayes: Achieved the highest accuracy at 96.28%, making it the most effective model for this task.
Logistic Regression: Provided moderate accuracy of around 50.5%.
K-Nearest Neighbors: Had the lowest accuracy at 37.1%, indicating it is less suitable for this dataset.

# Results
Naive Bayes emerged as the top-performing model, particularly for tasks requiring high accuracy. Visual comparisons, including bar plots for accuracy and line plots for F1 scores, help illustrate the performance differences among the models.

# Conclusion
The Naive Bayes model is recommended for music genre classification due to its superior accuracy. Logistic Regression showed average results, while KNN was less effective. Future work may include hyperparameter tuning, feature engineering, and exploring advanced models like Random Forests or Neural Networks.
