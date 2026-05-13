# Diabetes Prediction System

This project uses Machine Learning to predict the likelihood of diabetes in patients based on medical metrics. It features a comparison between Logistic Regression and Random Forest models and includes a web interface built with Gradio.

## Features
- **Data Preprocessing**: Handling missing values (zeros) using median imputation.
- **Scaling**: Feature standardization using StandardScaler.
- **Models**: Logistic Regression and Random Forest Classifier.
- **Evaluation**: Accuracy, F1-Score, ROC-AUC, and Confusion Matrices.
- **UI**: Interactive interface for real-time predictions.

## Installation
To run this project locally, install the dependencies:
`pip install -r requirements.txt`

## How to Use
1. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
2. Run all cells to train the model.
3. Use the Gradio link generated at the end to input patient data and see results.
