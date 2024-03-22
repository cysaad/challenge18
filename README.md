
# Student Loan Risk Assessment with Deep Learning

This project focuses on assessing the risk associated with student loans using a deep learning model. By analyzing a dataset of student loans, the model predicts the likelihood of loan repayment success, helping in making informed decisions about loan issuance. This README outlines the steps to prepare the data, compile and evaluate a deep neural network model, and predict loan repayment success.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running this project, ensure you have the following packages installed:

- pandas
- tensorflow
- scikit-learn
- numpy

You can install these packages using pip:

```bash
pip install pandas tensorflow scikit-learn numpy
```

### Data Preparation

The data for this project is sourced from a CSV file containing information about student loans. The preparation steps include reading the data, creating feature and target datasets, splitting these into training and testing datasets, and scaling the features.

### Model Compilation and Evaluation

The project uses TensorFlow's Keras to create a deep neural network model. The model is compiled with the `binary_crossentropy` loss function, the `adam` optimizer, and evaluates using accuracy as the metric. The model undergoes training with the prepared data, and its performance is evaluated on a test set.

### Predicting Loan Repayment Success

The trained model is used to predict the success of loan repayments on new data. Predictions are saved to a DataFrame, rounded to binary results, and a classification report is generated to assess the model's performance.

### Exporting and Importing the Model

The trained model is saved to a file named `student_loans.keras` for later use. Instructions are provided for exporting the model to this file and loading it from the file for making predictions.

## Usage

To use this project, follow the steps in the provided Jupyter Notebook or Python script:

1. **Prepare the Data**: Read the CSV, define features and target, split into train/test, and scale the features.
2. **Compile and Evaluate the Model**: Create and train the deep neural network, then evaluate its performance.
3. **Predict Loan Repayment Success**: Use the trained model to predict repayment success and analyze the predictions.
4. **Export/Import the Model**: Save the model for future use and load it as needed.



