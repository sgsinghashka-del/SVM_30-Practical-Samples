# SVM 30 Practical Samples

This repository contains a practical Jupyter Notebook for implementing Support Vector Machine (SVM) classifiers on real-world-inspired use cases. The project demonstrates how SVM can be used for classification problems in industrial and vehicle monitoring scenarios.

## Project Overview

The notebook includes multiple examples of SVM-based predictive modeling, covering:

- Battery health prediction
- Fuel theft detection
- Tyre replacement prediction
- Model evaluation using accuracy, classification reports, and confusion matrices
- User input-based prediction workflows
- Visualizations for performance analysis

## Included Examples

### 1. Battery Health Prediction
Predict whether a battery is:
- Healthy
- Weak
- Critical

Uses features such as:
- Charge cycles
- Voltage
- Temperature
- Capacity

### 2. Fuel Theft Detection
Detect suspicious fuel usage patterns based on:
- Fuel level
- Distance traveled
- Engine status
- Time of event

### 3. Tyre Replacement Prediction
Estimate whether tyres should be:
- Continue using
- Replace

Uses input features such as:
- Tread depth
- Mileage
- Pressure
- Age

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- matplotlib
- scikit-learn

## Repository Structure

- `SVM_30_Practical_Samples.ipynb` — Main notebook containing all model examples and demonstrations

## Requirements

Make sure you have Python 3.9+ installed.

Install the required packages:

```bash
pip install pandas matplotlib scikit-learn notebook
```

## How to Run

### Option 1: Jupyter Notebook locally

```bash
jupyter notebook
```

Then open `SVM_30_Practical_Samples.ipynb` from the notebook browser.

### Option 2: Google Colab

Open the notebook in Colab directly from GitHub or upload it to your Google Drive and run it there.

## Model Workflow

Each example follows a similar pipeline:

1. Create a sample dataset
2. Split data into training and testing sets
3. Scale features
4. Train an SVM classifier
5. Evaluate model performance
6. Use user inputs to predict the class
7. Visualize model results

## Example Output

The notebook prints:
- dataset preview
- model accuracy
- classification report
- confusion matrix
- prediction results based on new inputs

## Notes

This project is intended as a beginner-friendly hands-on introduction to SVM classification and practical data science workflows. It demonstrates how classical machine learning models can be applied to real-world monitoring and maintenance decisions.

## License

This project is provided for educational and demonstration purposes.

## Author

Created for practical SVM learning and experimentation.
