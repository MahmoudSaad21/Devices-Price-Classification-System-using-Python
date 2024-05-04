# Devices Price Classification System

The Devices Price Classification System is a machine learning project that predicts the price range of devices based on their specifications. The project consists of a Python project for model training and prediction.

## Project Structure

The project is organized as follows:

- `python_project/`: Contains the Python project for data preparation, model training, and prediction.

## Setup

To set up the project:

1. Clone the repository.
2. Set up a Python environment and install the required libraries for the Python project.

## Python Project

The Python project consists of the following key components:

- `train.py`: Handles data preparation and model training.
- `predict.py`: Makes predictions based on device specifications.

## Endpoints

The Python project includes a RESTful API implemented using Flask for serving predictions. The primary endpoint is `/predict_price`, which accepts POST requests with device specifications and returns the predicted price range.

## Testing and Usage

Use tools like Postman or Curl to test the API by sending POST requests to the `/predict_price` endpoint with device specifications in the request body.

## Hyperparameter Tuning

The Python project includes hyperparameter tuning using GridSearchCV to optimize the model's performance.

## Dependencies

- Python libraries: scikit-learn, pandas, Flask

