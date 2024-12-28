# 🔋 Electrical Energy Prediction using Artificial Neural Network (ANN)

## 🌟 Project Overview

This project focuses on predicting electrical energy consumption using an **Artificial Neural Network (ANN)**. By leveraging advanced machine learning frameworks such as **TensorFlow**, **Keras**, **Scikit-Learn**, and **Pandas**, we train a predictive model based on historical energy usage data. The model predicts future energy consumption and helps in energy management, resource optimization, and cost reduction.

## 🛠️ Technologies Used

- **TensorFlow**: A powerful framework used for building and training deep learning models.
- **Keras**: A high-level neural networks API running on top of TensorFlow, simplifying the process of building ANN models.
- **Scikit-Learn**: A library used for data preprocessing, splitting datasets, and evaluating model performance.
- **Python**: The programming language used for implementing the entire project.
- **Pandas**: A data manipulation library used to handle and process data in DataFrame format.

### 🖼️ Images of Libraries Used

- **TensorFlow**:
  ![TensorFlow Logo](https://upload.wikimedia.org/wikipedia/commons/2/2d/TensorFlow_logo.svg)

- **Keras**:
  ![Keras Logo](https://upload.wikimedia.org/wikipedia/commons/e/e4/Keras_logo.svg)

- **Scikit-Learn**:
  ![Scikit-Learn Logo](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png)

- **Pandas**:
  ![Pandas Logo](https://upload.wikimedia.org/wikipedia/commons/1/19/Pandas_logo.svg)

## 🔍 Project Description

The goal of this project is to predict electrical energy consumption using a **neural network** trained on historical data. The model analyzes past energy usage patterns and learns to make predictions about future consumption. This can be useful for utilities, businesses, and households aiming to optimize energy use and reduce costs.

### 📊 Key Steps in the Project

1. **Data Collection and Preprocessing**:
   - The dataset is loaded using **Pandas** and preprocessed by handling missing values, outliers, and scaling features for better performance during training.

2. **Model Development**:
   - The model is built using **Keras** and **TensorFlow**. The architecture consists of an input layer, hidden layers with activation functions like **ReLU**, and an output layer that predicts energy consumption.

3. **Training the Model**:
   - The model is trained using the **Adam optimizer** and **mean squared error (MSE)** loss function. The data is split into training and validation sets using **Scikit-Learn**.

4. **Evaluation and Testing**:
   - After training, the model's performance is evaluated on a separate test dataset to assess accuracy, **MSE**, and other metrics.
