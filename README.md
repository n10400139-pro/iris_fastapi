# Iris Species Prediction API

## Problem
Predict iris species (setosa, versicolor, virginica) based on 4 numerical features: sepal length, sepal width, petal length, petal width.

## Model
Logistic Regression trained on sklearn's iris dataset achieving ~98% accuracy.

## API Usage

### Endpoints

- `GET /` — Health check
- `POST /predict` — Predict species from JSON input:
  ```json
  {
    "features": [5.1, 3.5, 1.4, 0.2]
  }
