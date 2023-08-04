# Loan Status Prediction Model

This repository contains a Python-based Machine Learning model for predicting loan approval status.

## Getting Started

These instructions will help you to understand the content of the repository.

## Repository Structure

The repository contains a Jupyter notebook script (ipynb) which has been broken down into multiple sections to aid readability and understanding.

## Prerequisites

To run this script, you need to have the following libraries:

1. numpy
2. pandas
3. seaborn
4. scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas seaborn scikit-learn
```

## Dataset

The script uses a dataset from a `train.csv` file. This dataset contains various details about loan applicants and the status of their loan application (approved/rejected).

## Script Overview

1. **Data Collection and Processing**: The script begins with loading the dataset into a pandas DataFrame, checking for missing values, and dropping them if found. Some categorical values are replaced with numerical equivalents for easier processing.

2. **Data Visualization and Preprocessing**: Here, different columns are plotted to understand their relationship with the loan status. Categorical variables are converted into dummy/indicator variables.

3. **Data Split**: The data is split into training and test data, with 80% for training and 20% for testing.

4. **Training the Model**: A Support Vector Machine model is used for training the data.

5. **Model Evaluation**: The model is evaluated using the accuracy score on both training data and test data.

## Running the script

The script can be run in any python environment that supports the libraries. It is recommended to use Jupyter notebooks or Google colab for easy visualization and debugging.

## Accuracy

The model's performance is evaluated using the accuracy score metric on the training and test data.
