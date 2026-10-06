# Customer Churn Prediction

An Artificial Neural Network (ANN) built with TensorFlow/Keras to predict whether a bank customer will churn (close their account). Deployed as an interactive web app with Streamlit.

---

## Quickstart

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the Streamlit App
```bash
streamlit run app.py
```

---

## Project Structure
* `experiments.ipynb` – Data preprocessing, model building, and training with TensorBoard.
* `prediction.ipynb` – Inference pipeline testing for single-customer input.
* `app.py` – Interactive Streamlit web application.
* `model.keras` – Trained Deep Learning model.
* `*.pkl` – Saved Scaler, LabelEncoder, and OneHotEncoder artifacts.
