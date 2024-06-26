# Vaccine-Prediction

This repository contains the code and data for predicting xyz and seasonal flu
vaccines uptake using machine learning techniques. The main components of this project are:

- `Code.ipynb`: Jupyter notebook containing the data preprocessing, model training, and evaluation steps.
- `submission.csv`: The submission file with predicted probabilities for the test set.

## Dataset

The dataset includes information about respondents and their vaccination status for the xyz flu and seasonal flu. The data is split into training and test sets.

## Files

- `training_set_features.csv`: Features for the training set.
- `training_set_labels.csv`: Labels for the training set.
- `test_set_features.csv`: Features for the test set.
- `submission.csv`: The predicted probabilities for the test set.

## Method

### Data Preprocessing

- Handled missing values by imputation and categorical variables by encoding.
- Scaled numerical features to standardize the data.

### Model Training

-Split the training data.
- Trained a Random Forest classifier to predict the probability of receiving the xyz flu vaccine and the seasonal flu vaccine.


### Evaluation

- Calculated the area under the receiver operating characteristic curve (ROC AUC) for each of the two target variables.
- The mean of these two scores is used as the overall evaluation metric.

## Result
- Predict probabilities and created the submission file.

## Usage

To run the code in the Jupyter notebook, follow these steps:

## Usage

To run the code in the Jupyter notebook, follow these steps:

1. Clone this repository:
   ```sh
   git clone https://github.com/savi1708/Vaccine_Prediction.git
   cd Vaccine_Prediction


