# Week4NLP

# Text Classification using Random Forest

## Overview
This Python script demonstrates text classification using a Random Forest classifier. It reads in training and testing data from CSV files, preprocesses the text data, trains the model, makes predictions, and generates a submission file.

## Prerequisites
Before running this code, ensure you have the following libraries installed:

- pandas
- scikit-learn (sklearn)

You can install these libraries using pip:

## Usage
1. Place your training data in a file named "trainc.csv" and your testing data in a file named "testc.csv" in the same directory as this script.
2. Modify the hyperparameters for the Random Forest classifier if needed. You can adjust `n_estimators`, `min_samples_split`, and `min_samples_leaf` for optimization.
3. Run the script using Python.

```bash
python text_classification.py
