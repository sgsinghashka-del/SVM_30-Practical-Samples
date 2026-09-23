# Support Vector Machine: 30 Practical Samples

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/sgsinghashka-del/SVM_30-Practical-Samples/blob/main/SVM_30_Practical_Samples.ipynb)

A hands-on machine learning portfolio project demonstrating how **Support Vector Machine (SVM)** classification can be applied to practical monitoring, maintenance, and anomaly-detection scenarios.

The notebook uses small, clearly structured sample datasets to guide the reader through the complete workflow: feature preparation, train/test splitting, standardization, model training, evaluation, visualization, and prediction from user-provided inputs.

> **Educational note:** The datasets in this project are constructed examples for learning and demonstration. The reported metrics should not be interpreted as production performance or as evidence for real-world operational decisions.

## Table of Contents

- [Project Highlights](#project-highlights)
- [Use Cases](#use-cases)
- [Machine Learning Workflow](#machine-learning-workflow)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Running the Notebook](#running-the-notebook)
- [Repository Structure](#repository-structure)
- [Results and Visualizations](#results-and-visualizations)
- [Academic and Portfolio Context](#academic-and-portfolio-context)
- [Future Improvements](#future-improvements)
- [License](#license)

## Project Highlights

- Applies an RBF-kernel `SVC` model to multiple classification tasks.
- Uses `StandardScaler` to normalize numerical features before SVM training.
- Demonstrates stratified train/test splitting for classification datasets.
- Reports accuracy and detailed precision, recall, and F1-score metrics.
- Builds confusion matrices to inspect class-level predictions.
- Accepts interactive user input for new predictions.
- Includes charts for communicating model outputs and class distributions.

## Use Cases

### 1. Battery Health Prediction

Classifies a battery as **Healthy**, **Weak**, or **Critical** using:

- Charge cycles
- Voltage
- Temperature
- Capacity

### 2. Fuel Theft Detection

Classifies vehicle fuel activity as **Normal** or **Suspicious** using:

- Fuel level
- Distance traveled
- Engine status
- Event time

### 3. Tyre Replacement Prediction

Predicts whether a tyre should **Continue** in service or be **Replaced** using:

- Tread depth
- Mileage
- Pressure
- Tyre age

## Machine Learning Workflow

Each example follows a reproducible supervised-learning pipeline:

1. Construct a sample dataset with domain-inspired features.
2. Separate predictor variables from the target label.
3. Create stratified training and testing subsets.
4. Fit a `StandardScaler` on the training data only.
5. Train an SVM classifier with an RBF kernel.
6. Generate predictions for the held-out test set.
7. Evaluate the model with accuracy and a classification report.
8. Inspect results with a confusion matrix or other visualization.
9. Transform new user inputs and generate a prediction.

## Technologies

- **Python 3.9+**
- **pandas** — tabular data preparation
- **scikit-learn** — preprocessing, SVM modeling, and evaluation
- **matplotlib** — charts and confusion-matrix visualization
- **Jupyter Notebook / Google Colab** — interactive execution

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sgsinghashka-del/SVM_30-Practical-Samples.git
cd SVM_30-Practical-Samples
```

### 2. Install dependencies

```bash
python -m pip install pandas matplotlib scikit-learn notebook
```

For an isolated environment:

```bash
python -m venv .venv
source .venv/bin/activate       # macOS/Linux
.venv\\Scripts\\activate      # Windows
python -m pip install pandas matplotlib scikit-learn notebook
```

## Running the Notebook

### Jupyter Notebook

```bash
jupyter notebook SVM_30_Practical_Samples.ipynb
```

Run the cells from top to bottom. The notebook will display evaluation metrics, request example inputs, and generate visualizations.

### Google Colab

Use the **Open in Colab** badge at the top of this README, or open the notebook directly:

[Open `SVM_30_Practical_Samples.ipynb` in Google Colab](https://colab.research.google.com/github/sgsinghashka-del/SVM_30-Practical-Samples/blob/main/SVM_30_Practical_Samples.ipynb)

## Repository Structure

```text
SVM_30-Practical-Samples/
├── SVM_30_Practical_Samples.ipynb  # Interactive SVM examples
└── README.md                       # Project documentation
```

## Results and Visualizations

When executed, the notebook produces:

- Dataset previews for each use case
- Accuracy scores
- Classification reports
- Confusion matrices
- A fuel-status distribution chart
- Interactive predictions from entered feature values

The notebook itself is the source of truth for the latest generated outputs. Because the examples use small synthetic datasets, results may be highly sensitive to the selected train/test split and should be interpreted as demonstrations of the workflow rather than benchmarks.

## Academic and Portfolio Context

This project is suitable for demonstrating foundational competency in:

- Supervised machine learning
- Binary and multiclass classification
- Feature scaling and data preprocessing
- SVM model selection and use of kernel methods
- Classification evaluation and error analysis
- Translating domain questions into predictive features

For a research-oriented extension, the project could be evaluated using cross-validation, hyperparameter tuning, larger domain datasets, and confidence intervals around performance estimates.

## Future Improvements

- Add cross-validation and automated hyperparameter search for `C` and `gamma`.
- Compare SVM performance with tree-based and linear baseline models.
- Replace sample data with validated real-world datasets.
- Add data-quality checks and reusable preprocessing pipelines.
- Track precision, recall, F1-score, and class-specific costs more systematically.
- Add unit tests and a non-interactive command-line prediction interface.
- Save trained models with versioned metadata for reproducible inference.

## License

This project is provided for educational and demonstration purposes. Add a repository license file if you intend to distribute or reuse the project under a specific open-source license.

## Author

**Ashka Singh**

- GitHub: [@sgsinghashka-del](https://github.com/sgsinghashka-del)
