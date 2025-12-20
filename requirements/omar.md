# Model Development & Experiments

Responsible for data preprocessing, model implementation, training, and experimental evaluation.

## Data Preprocessing

- Load the DIDA (10k) dataset
- Convert images to 784-dimensional feature vectors
- Normalize pixel values to the range [0,1]
- Split dataset into training (80%) and testing (20%) sets
- Save processed datasets for reuse

## Model Implementation (scikit-learn)

- Implement Multi-layer Perceptron (MLP) Neural Network
  - Minimum of 2 hidden layers
  - Tune hyperparameters:
    - Number of neurons per layer
    - Learning rate
    - Number of epochs
    - Batch size
- Implement Logistic Regression
  - Multi-class classification setup
  - Handle convergence criteria
- Implement Linear Regression
  - Apply One-vs-All (OvA) strategy manually
- Implement Naive Bayes Classifier (GaussianNB)

## Experiments & Validation

- Implement 5-fold cross-validation
- Compute performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Report mean and standard deviation for all metrics
- Measure training time for each model
- Store experimental results and metrics
