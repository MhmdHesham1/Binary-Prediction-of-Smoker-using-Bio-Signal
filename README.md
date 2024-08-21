Binary Prediction of Smoker Status Using Bio-Signals
Project Overview

This project aims to predict the smoker status (binary classification) of individuals based on various bio-signals. The model is trained using the CatBoostClassifier from the catboost library and evaluated using common classification metrics.
Data Preparation

    Data Source: The dataset used in this project includes various bio-signals as features and a binary target indicating smoker status.
    Preprocessing: The data undergoes preprocessing steps including handling missing values, normalization, and feature selection.

Model Development

    Model Used: CatBoostClassifier from the catboost library.
    Hyperparameters: The model is configured with the following key hyperparameters:
        iterations=100
        depth=2
        learning_rate=0.1
        random_seed=33
        logging_level='Silent'

Evaluation

The model's performance is evaluated using the following metrics:

    Accuracy: Measures the proportion of correctly predicted instances.
    Precision: Measures the accuracy of positive predictions.
    Recall: Measures the ability to capture all positive instances.
    F1 Score: Harmonic mean of precision and recall.

Results

The model's results are summarized as follows:

    Accuracy: X.XX
    Precision: X.XX
    Recall: X.XX
    F1 Score: X.XX

Conclusion

The model demonstrates [high/adequate/low] predictive performance for predicting smoker status using bio-signals. Future work may involve [further tuning the model, exploring additional features, using different models, etc.].
How to Run

    Clone this repository.
    Install the necessary dependencies: pip install -r requirements.txt.
    Open the Jupyter notebook and run the cells in sequence to train the model and evaluate its performance.
