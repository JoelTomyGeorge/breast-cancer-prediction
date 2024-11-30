# Breast Cancer Prediction Web App

This project is a web application built with **Streamlit** that predicts whether a tumor is **Malignant** or **Benign** based on user inputs for selected features from the Breast Cancer dataset. The model is a trained Artificial Neural Network (ANN) built using **scikit-learn**.

## Features

- **Interactive Web App**: Users can input features via sliders, and the app will predict the tumor's type (Malignant/Benign).
- **Model Training**: The ANN model is trained on the Breast Cancer dataset, using feature selection to improve the model’s performance.
- **Preprocessing**: The input features are scaled using a saved scaler to ensure the model performs optimally.

## Technologies Used

- **Streamlit**: For building the interactive web interface.
- **scikit-learn**: For training and evaluating the model.
- **pandas** and **numpy**: For data manipulation and processing.
- **pickle**: For saving and loading the trained model and scaler.
- **Python 3.12**: Programming language used for development.

## Requirements

To run this project locally, make sure you have the following libraries installed:

- **Streamlit**: For creating the web application.
- **scikit-learn**: For the machine learning model.
- **pandas**: For handling data.
- **numpy**: For numerical operations.

### Install Dependencies

First, clone the repository and navigate to the project folder.

```bash
git clone https://github.com/yourusername/breast-cancer-prediction.git
cd breast-cancer-prediction
