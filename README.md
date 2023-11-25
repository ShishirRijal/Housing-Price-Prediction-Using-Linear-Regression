# Housing Price Prediction 

Welcome to the Housing Price Prediction Model repository! This project utilizes a Linear Regression model to predict housing prices based on various features. The model is trained on a dataset containing information about housing features such as area, bedrooms, bathrooms, and more.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Libraries Used](#libraries-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting housing prices is a critical task in the real estate industry. This project aims to provide a simple yet effective solution using a Linear Regression model. By analyzing various features such as area, bedrooms, and bathrooms, the model can predict housing prices, providing valuable insights for both buyers and sellers.

## Features

The dataset includes the following features:

- `price`: The target variable representing the housing price.
- `area`: The area of the housing property.
- `bedrooms`: The number of bedrooms in the property.
- `bathrooms`: The number of bathrooms in the property.
- `stories`: The number of stories in the property.
- `mainroad`: Whether the property is located on the main road (binary: 1 for yes, 0 for no).
- `guestroom`: Whether the property has a guestroom (binary: 1 for yes, 0 for no).
- `basement`: Whether the property has a basement (binary: 1 for yes, 0 for no).
- `hotwaterheating`: Whether the property has hot water heating (binary: 1 for yes, 0 for no).
- `airconditioning`: Whether the property has air conditioning (binary: 1 for yes, 0 for no).
- `parking`: The number of parking spaces available in the property.
- `prefarea`: Whether the property is in a preferred area (binary: 1 for yes, 0 for no).
- `furnishingstatus`: The furnishing status of the property.

## Libraries Used

The following Python libraries are used in this project:

- `matplotlib`: Data visualization library.
- `numpy`: Numerical computing library.
- `pandas`: Data manipulation and analysis library.
- `seaborn`: Statistical data visualization library.
- `scikit-learn`: Machine learning library for model training and evaluation.

## Installation

To run this project, make sure you have Python and the required libraries installed. You can install the necessary dependencies using the following command:

```bash

pip install matplotlib numpy pandas seaborn scikit-learn

```

## Usage
Clone the repository and navigate to the project directory. Run the Jupyter notebook or script to see the model in action. Adjust the parameters or features as needed for your specific use case.

## Model Training
The Linear Regression model is trained on the dataset using the train_test_split method for splitting the data into training and testing sets. One-hot encoding is applied to categorical features, and feature scaling is performed using MinMaxScaler to ensure optimal model performance.

## Evaluation
The model's performance is evaluated using metrics such as R-squared score and mean squared error. Visualization tools like matplotlib and seaborn are employed to gain insights into the data and evaluate the model's predictions.
