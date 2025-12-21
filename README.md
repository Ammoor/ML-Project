# Handwritten Digit Recognition

A machine learning project for recognizing handwritten digits using multiple classification algorithms including MLP, Logistic Regression, Linear Regression (OVA), and Naive Bayes.

---

## Project Structure

```
handwritten-digit-recognition/
│
├── data/
│   ├── raw/                          # Original unprocessed dataset files
│   │
│   └── processed/                    # Preprocessed data ready for training
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb          # Data loading, cleaning, and preprocessing
│   │
│   ├── 02_mlp_model.ipynb                   # Multi-Layer Perceptron implementation
│   │
│   ├── 03_logistic_regression.ipynb         # Logistic Regression classifier
│   │
│   ├── 04_linear_regression_ova.ipynb       # Linear Regression with One-vs-All approach
│   │
│   ├── 05_naive_bayes.ipynb                 # Naive Bayes classifier
│   │
│   ├── 06_cross_validation.ipynb            # Cross-validation experiments
│   │
│   └── 07_evaluation_and_comparison.ipynb   # Model evaluation and comparison
│
├── results/
│   ├── metrics/                      # Performance metrics for each model (accuracy, precision, recall, F1)
│   │
│   ├── confusion_matrices/           # Confusion matrix visualizations for each model
│   │
│   └── plots/                        # Comparison charts and training visualizations
│
├── reports/
│   ├── figures/                      # Final figures for the report
│   │
│   └── (report files)                # Final project report documentation
│
├── presentation/                     # Presentation slides for project defense
│
├── requirements/                     # Project dependencies and setup instructions
│
├── team/                             # Team member information and contributions
│
└── README.md                         # Project overview and documentation
```

---

## Folder Descriptions

| Folder | Description |
|--------|-------------|
| `data/raw/` | Contains the original, unprocessed dataset (DIDA 10K handwritten digits) |
| `data/processed/` | Stores preprocessed NumPy arrays (train/test splits) ready for model training |
| `notebooks/` | Jupyter notebooks for data preprocessing, model training, and evaluation |
| `results/metrics/` | CSV files containing performance metrics (accuracy, precision, recall, F1-score) |
| `results/confusion_matrices/` | PNG images of confusion matrices for each classifier |
| `results/plots/` | Visualization plots comparing model performance |
| `reports/figures/` | Final figures and charts for the project report |
| `reports/` | Contains the final project report (PDF) |
| `presentation/` | PowerPoint/slides for the final project presentation |
| `requirements/` | Lists all Python dependencies needed to run the project |
| `team/` | Documentation of team members and their contributions |

---

## Models Implemented

1. **Multi-Layer Perceptron (MLP)** - Neural network classifier
2. **Logistic Regression** - Probabilistic linear classifier
3. **Linear Regression (One-vs-All)** - Linear model adapted for classification
4. **Naive Bayes** - Probabilistic classifier based on Bayes' theorem

---

## Getting Started

1. Clone the repository
2. Install dependencies from `requirements/`
3. Run notebooks in order (01 → 07)
4. View results in the `results/` folder

---

## Team

See the `team/` folder for team member details.
