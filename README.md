# Customer Churn Prediction with a Live Web API

This project demonstrates a complete end-to-end machine learning workflow. It involves training a logistic regression model to predict customer churn based on the Telco Customer Churn dataset, and then deploying that model via a REST API built with Flask.

The final goal is to create a simple web frontend where a user can input customer data and receive a live churn prediction from the trained model.

## Project Components

* **`churn_prediction_model.ipynb`**: A Jupyter Notebook containing all steps for data loading, exploratory data analysis (EDA), data preprocessing, model training, and evaluation.
* **`app.py`**: A Flask web server that loads the trained model and scaler, and exposes a `/predict` endpoint to serve predictions.
* **`churn_model.joblib`**: The saved, pre-trained Scikit-learn model object.
* **`scaler.joblib`**: The saved Scikit-learn StandardScaler object used to preprocess the data.

## Technologies Used

* **Data Science & ML:** Python, Pandas, NumPy, Scikit-learn, Joblib
* **API & Backend:** Flask, Flask-CORS
* **Environment:** Jupyter Notebook

## How to Run

1.  **Clone the repository.**
2.  **Install dependencies:** `pip install -r requirements.txt`
3.  **Run the API:** `python app.py`
4.  The server will be running at `http://127.0.0.1:5000`.
