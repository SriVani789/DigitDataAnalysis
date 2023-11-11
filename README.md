# Handwritten Digit Recognition with Random Forest Classifier

## Overview
This project focuses on recognizing handwritten digits using the famous Optical Recognition of Handwritten Digits dataset. The classification model is implemented using the Random Forest Classifier.

## Dataset
The dataset consists of 8x8 images of handwritten digits (0 to 9) and their corresponding labels. The dataset contains 1797 instances, each represented as a 64-dimensional array.

## Data Description
- Number of Instances: 1797
- Number of Attributes: 64 (8x8 image pixels)
- Attribute Information: Integer values in the range 0 to 16
- Creator: E. Alpaydin
- Date: July 1998

For more information on the dataset, refer to the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Optical+Recognition+of+Handwritten+Digits).

## Preprocessing
1. Loaded the dataset using scikit-learn's `load_digits`.
2. Extracted relevant information like data, target, feature names, etc.

## Model Training
1. Split the dataset into training and testing sets.
2. Utilized the Random Forest Classifier with 600 estimators for model training.

## Evaluation
1. Calculated accuracy on the test set.
2. Generated a classification report including precision, recall, and F1-score for each digit class.

## Usage
1. Clone the repository.
2. Ensure you have Python and necessary libraries installed.
3. Run the script (`random_forest_digit_recognition.py`).
4. Interact with the Random Forest model for digit recognition.
