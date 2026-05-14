# Housing Price Prediction API

This project trains a Linear Regression model using the California Housing dataset from Scikit-learn and deploys it using a Flask API.

## Files

- `train_model.py`: Trains the model and saves it as `model.pkl`
- `app.py`: Flask API for prediction
- `model.pkl`: Saved trained model
- `requirements.txt`: Required Python libraries

## API Endpoint

### Home

GET `/`

Returns:

```text
Housing Price Prediction API is running.