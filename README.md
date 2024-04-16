# Introduction
The goal of this project is to predict sleep states (awake/asleep) based on physiological data such as heart rate (BPM). The dataset used in this analysis contains records of BPM measurements along with corresponding timestamps.

# Dataset
The dataset (sleep_data.csv) consists of the following columns:

- BPM: Heart rate in beats per minute.
- Time: Timestamp of the measurement.
- State: Awake or Asleep based on the ranges.

# Preprocessing
- Converted time column to timestamp format.
- Applied a function to handle singular instances of "Asleep" State in a continuous rows of "Awake" State (Vice Versa).

# Modeling

- Logistic Regression:
  - Trained a logistic regression model to predict sleep states.
  - Used cross-validation to evaluate model performance.
  - Analyzed confusion matrix, precision, recall, and F1-score.

- Decision Tree:
  - Trained a decision tree classifier for sleep state prediction.
  - Evaluated model performance using cross-validation and various metrics.
