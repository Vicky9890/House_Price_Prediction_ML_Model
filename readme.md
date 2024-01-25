# House🏡 Price Prediction using Mechine Learning tools 

This project aims to predict house prices using machine learning techniques, specifically leveraging the TensorFlow library for building neural networks and Scikit-Learn for data preprocessing. By utilizing these powerful tools, we aim to create a robust model that can accurately predict house prices based on given features.

## Introduction

Predicting house prices is a common and challenging problem in the field of real estate and finance. Machine learning provides a powerful approach to tackle this problem by learning patterns and relationships from historical data. In this project, we employ a neural network, implemented with TensorFlow, to capture complex dependencies in the data and make accurate predictions.

## Requirements 

Ensure you have the following dependencies installed before running the model:

- pandas
- tensorflow
- matplotlib
- scikit-learn

You can install these requirements using the following command:

```bash
pip install pandas matplotlib scikit-learn tensorflow
```

## Usage

To use the House Price Prediction Model, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Vicky9890/House_Price_Prediction_ML_Model.git
```

2. Navigate to the project directory:
```bash
cd House_Price_Prediction_ML_Model
```

3. Run the Classification model:
```bash
jupyter-notebook House_Price_Prediction.ipynb
```

The model performs the following steps:

- Loads the dataset.
- Preprocesses the data, including scaling numerical features.
- Splits the data into training and testing sets.
- Builds an ANN model using TensorFlow.
- Compiles and trains the model.
- Evaluates the model on the testing data.
- Visualizes the loss and accuracy during training.