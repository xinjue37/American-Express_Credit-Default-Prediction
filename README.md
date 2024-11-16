# American-Express_Credit-Default-Prediction

## Main Outcome
* Predict credit default probability from 18-month customer profiles using binary classification.
* Engineer features from 16GB+ datasets in batches for optimized ML model input.
* Develop ANN, XGBoost, and CatBoost models for precise credit default prediction.

## Directory Structure
|-- 1. Get All Data (1013, 59, 14)    # To process the data part by part
|-- 2. Concatenate the dataset.ipynb  # Concatenate all the process data
|-- 3.1 ANN_14.ipynb                  # Train the ANN model on the customer that have 1-4 rows of data
|-- 3.2 ANN_59.ipynb                  # Train the ANN model on the customer that have 5-9 rows of data 
|-- 3.3 ANN_1013.ipynb                # Train the ANN model on the customer that have 10-13 rows of data
|-- 3.4 XGBoost_CatBoost.ipynb        # Train the XGBoost & CatBoost model on customers
|-- 4. Predict outcome.ipynb          # Predict on test set and submit on kaggle
