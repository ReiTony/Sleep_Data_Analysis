# Introduction
The goal of this project is to predict sleep states (awake/asleep) based on physiological data such as heart rate (BPM) and time. The dataset used in this analysis contains records of BPM measurements along with corresponding timestamps.

# Dataset
The dataset (sleep_data.csv) consists of the following columns:

- BPM: Heart rate in beats per minute.
- Time: Timestamp of the measurement.
- BPM_change_threshold: A binary indicator (0/1) representing whether there was a significant change in BPM.

# Preprocessing
- Converted time column to timestamp format.
- Applied a threshold to detect significant changes in BPM and created a binary feature (BPM_change_threshold).

# Modeling

- Logistic Regression:
  - Trained a logistic regression model to predict sleep states.
  - Used cross-validation to evaluate model performance.
  - Analyzed confusion matrix, precision, recall, and F1-score.

- Decision Tree:
  - Trained a decision tree classifier for sleep state prediction.
  - Evaluated model performance using cross-validation and various metrics.
