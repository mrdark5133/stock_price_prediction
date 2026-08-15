# Indian Stock Price Predictor — Streamlit

This version keeps the user interface style of the uploaded `app.py`, but uses the trained `model.pkl` instead of retraining the XGBoost model on every click.

## Files required by Streamlit Community Cloud

- `app.py`
- `model.pkl`
- `requirements.txt`

The app fetches live NSE stock data using Yahoo Finance and uses the pickle model for prediction.

## Important

`model.pkl` must be generated with the same feature columns used by `app.py`.

Do not rename `model.pkl`.

## Streamlit Cloud

Set the main file to:

`app.py`

The repository should contain:

```text
app.py
model.pkl
requirements.txt
```

Educational project only — not financial advice.
