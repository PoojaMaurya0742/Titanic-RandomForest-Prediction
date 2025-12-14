Titanic Random Forest Prediction

This project predicts the survival of passengers on the Titanic using a Random Forest Classifier. The notebook demonstrates a complete machine learning workflow, including data preprocessing, model training, and prediction generation.

Project Overview

Objective: Predict survival of Titanic passengers.

Dataset: Titanic train and test datasets.

Model: Random Forest Classifier.

Accuracy: ~79.88% on validation set.

Files

data/train.csv : Training dataset

data/test.csv : Test dataset

notebooks/submission-csv.ipynb : Full Python notebook with preprocessing, model training, evaluation, and submission generation

Dependencies

Python 3.x

Pandas

NumPy

Scikit-learn

Seaborn

Matplotlib

Install dependencies via:

pip install -r requirements.txt

Usage Instructions

Clone the repository

git clone https://github.com/PoojaMaurya0742/Titanic-RandomForest-Prediction.git


Navigate to the project folder

cd Titanic-RandomForest-Prediction


Open the notebook
Launch submission-csv.ipynb using Jupyter Notebook or JupyterLab.

Run all cells
The notebook will:

Load and preprocess the data

Handle missing values

Encode categorical features

Train a Random Forest model

Evaluate model performance

Generate the submission file

Submission file
After running all cells, submission.csv will be created in the working directory. This CSV is ready for submission.

Notes

Both train.csv and test.csv are included in the data/ folder.

All preprocessing steps are implemented in the notebook.

This repository is intended for educational purposes and to demonstrate a complete machine learning workflow.
