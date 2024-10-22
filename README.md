# Spam Classification Project

This project explores different machine learning algorithms for classifying emails as spam or not spam using the Spambase dataset. 

## Dataset

The Spambase dataset contains a collection of emails labeled as spam or not spam. It includes various features extracted from the email content, such as word frequencies and punctuation characteristics.


## Algorithms

The project evaluates the following machine learning algorithms:

- **k-Nearest Neighbors (kNN):** A classification algorithm based on the proximity of data points.
- **Logistic Regression:** A statistical model that predicts the probability of a categorical outcome.
- **Decision Tree:** A tree-based model that makes decisions based on a series of rules.
- **Support Vector Machines (SVM):** A model that finds the optimal hyperplane to separate data points into different classes.


## Evaluation Metrics

The performance of each algorithm is assessed using the following metrics:

- **Accuracy:** The proportion of correctly classified instances.
- **Precision:** The proportion of true positive predictions among all positive predictions.
- **Recall:** The proportion of true positive predictions among all actual positive instances.
- **F1-score:** The harmonic mean of precision and recall.
- **AUC:** Area under the ROC curve, measuring the model's ability to distinguish between classes.


## Project Structure

The project consists of the following parts:

- **Data Loading:** Loading the dataset from a CSV file located in Google Drive.
- **Data Exploration:** Examining the basic statistics and characteristics of the dataset.
- **Model Training and Evaluation:** Training and evaluating each algorithm using train-test split and cross-validation.
- **Hyperparameter Tuning:** Exploring different hyperparameter settings for each algorithm.
- **Model Comparison:** Comparing the performance of different algorithms and identify the best performing one.


## Running the Project

1. **Google Colab:** This project is designed to be executed in Google Colab.
2. **Data:** Ensure the Spambase dataset is available in your Google Drive.
3. **Dependencies:** Necessary Python libraries are imported within the code, you need to run the cells to ensure the libraries are installed.
