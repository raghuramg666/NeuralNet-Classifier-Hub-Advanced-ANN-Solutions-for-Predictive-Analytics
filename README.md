# NeuralNet Classifier Hub: Advanced ANN Solutions for Predictive Analytics

Welcome to the NeuralNet Classifier Hub. This repository is designed to showcase the application of artificial neural networks (ANNs) in tackling complex classification problems. With models developed for scenarios like customer churn prediction and salary forecasting, this project illustrates the adaptability of ANNs to a variety of datasets and analytical challenges.

## Project Overview

This project contains a collection of Jupyter notebooks and Python scripts dedicated to demonstrating the effectiveness of ANNs in predictive analytics. It includes a series of pre-trained models, data preprocessing tools, and detailed notebooks that outline every step of the model training process, methods for hyperparameter tuning, and the implementation of predictions.

## Project Structure

- Churn_Modelling.csv: This is the dataset that has been used for developing the model that predicts customer churn. It contains customer data and their churn status which the model uses to learn patterns.
- experiments.ipynb: This notebook includes initial testing and experimentation with the ANN models, providing a sandbox environment for exploring different architectures and configurations.
- hyperparametertuningann.ipynb: This notebook focuses on the optimization of ANN models through hyperparameter tuning, using techniques like grid search and randomized search to find the most effective model settings.
- prediction.ipynb: This notebook is used to demonstrate how the trained models can be applied to make predictions. It provides practical examples of how to input new data and interpret the output of the models.
- salaryregression.ipynb: Focuses on creating an ANN model to predict salaries based on multiple input features such as education level, job position, and experience.
- app.py: A Flask web application that is set up to serve the predictions from the trained models. This script turns the models into a usable service that can be interacted with through a web interface.
- model.h5: Contains the trained ANN model saved in the HDF5 file format, allowing for easy loading and deployment of the model without retraining.
- label_encoder_gender.pkl, onehot_encoder_geo.pkl, scaler.pkl: These files are serialized versions of preprocessing tools used in the model pipeline, ensuring that input data is consistently transformed in the same way as the training data.

## Getting Started

### Prerequisites

To run this project, you will need Python 3.x installed on your machine along with several major libraries that are fundamental to data science and machine learning projects:
- TensorFlow
- Keras
- Scikit-learn
- Flask
- Jupyter

### Installation

To set up the project environment, follow these steps:
- Clone this repository to your local machine:
  ```bash
  git clone <repository-url>
  cd ANN_classification-main
  ```
- Install the necessary Python libraries:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Project

- To engage with the model training and evaluation process, start the Jupyter notebooks:
  ```bash
  jupyter notebook experiments.ipynb
  ```
- To launch the Flask application and interact with the predictive models via a web interface:
  ```bash
  python app.py
  ```

