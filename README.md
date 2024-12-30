# Movie-Genre-Classification

Overview
This project aims to classify movies into their respective genres based on their plot summaries or descriptions. The training and testing datasets contain movie genres and corresponding descriptions, enabling the development of a machine learning model for genre prediction.

Objectives
Preprocess and clean textual data to extract meaningful features.
Convert movie descriptions into numerical representations using TF-IDF or word embeddings (e.g., Word2Vec, GloVe).
Train a Support Vector Classifier (SVC) to predict movie genres based on the provided descriptions.
Evaluate the model's performance using standard classification metrics.
Dataset
The dataset used in this project consists of:

Input: Movie descriptions or plot summaries (textual data).
Output: Corresponding genres for each movie.
The dataset is divided into training and testing sets for model development and evaluation.
Project Workflow
Data Preprocessing

Cleaned the textual data by:
Removing noise (e.g., punctuation, special characters).
Lowercasing text and removing stopwords.
Tokenizing the text and applying stemming/lemmatization.
Extracted features using TF-IDF to convert text into numerical representations.
Model Training

Trained a Support Vector Classifier (SVC) to classify movies into genres.
Tuned hyperparameters to optimize the classifier's performance.
Evaluation Metrics

Evaluated the model using:
Accuracy: Measures overall correctness.
Precision: Evaluates the relevancy of the predicted genres.
Recall: Measures the proportion of correctly identified genres.
F1-Score: Combines precision and recall into a single metric.
Results
The Support Vector Classifier successfully categorized movies into their respective genres based on their descriptions, achieving optimal performance using the selected preprocessing and feature extraction techniques.
