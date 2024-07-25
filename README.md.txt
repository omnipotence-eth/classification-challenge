# Spam Detector

This project implements a spam detector using machine learning techniques to classify emails as spam or not spam.

## Dataset

Spam-data set

## Models

Two models were implemented and compared:

1. Logistic Regression
2. Random Forest Classifier

## Results

### Logistic Regression
- Training Data Score: 0.9258
- Testing Data Score: 0.9227

### Random Forest Classifier
- Accuracy Score: 0.9531

The Random Forest Classifier outperformed the Logistic Regression model on this dataset.

## Implementation Details

- Data was split into training and testing sets
- Features were scaled using StandardScaler
- Models were trained on the scaled training data and evaluated on the test data

## Libraries Used

- pandas
- scikit-learn

## Files

- `spam_detector.ipynb`: Jupyter notebook containing the full analysis and model implementation

## Usage

1. Ensure you have the required libraries installed
2. Run the Jupyter notebook to see the full analysis and results