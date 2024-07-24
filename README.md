# Kidney Stone Treatment Prediction

This project aims to predict the treatment success for kidney stones based on stone size and treatment type using Logistic Regression.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Features](#features)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project involves building a machine learning model to predict the success of different treatments for kidney stones. The model is built using Logistic Regression and is trained on a dataset containing information about stone size and treatment type.

## Installation
1. **Clone the repository:**

   git clone https://github.com/your-username/kidney-stone-prediction.git
   cd kidney-stone-prediction


2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Run the main script to train the model and make predictions:**
   ```bash
   python main.py
   ```

2. **View the results:**
   - The predictions and evaluation metrics will be saved as CSV files: `predictions.csv` and `evaluation_metrics.csv`.

3. **Visualizations:**
   - Confusion matrix, feature importance, and ROC curve plots will be displayed during execution.

## Dataset
The dataset used for this project contains information about kidney stone size and treatment type. It includes the following columns:
- `stone_size`: Size of the kidney stone (e.g., 'small', 'large')
- `treatment`: Type of treatment (e.g., 'A', 'B')
- `success`: Whether the treatment was successful (1 for success, 0 for failure)

## Features
- **Data Preprocessing:** Label encoding for categorical data.
- **Model Training:** Logistic Regression to predict treatment success.
- **Evaluation Metrics:** Precision, Recall, Accuracy, Confusion Matrix.
- **Visualizations:** Confusion Matrix Heatmap, Feature Importance Plot, ROC Curve.
- **Cross-Validation:** 5-fold cross-validation for robust model evaluation.

## Results
The model achieved the following performance metrics on the test set:
- **Precision:** X.XX
- **Recall:** X.XX
- **Accuracy:** X.XX
- **Average Cross-Validation Score:** X.XX

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
