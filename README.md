# Customer Churn Prediction with a Live Web API and Deployed Frontend

This project demonstrates a complete end-to-end machine learning workflow using the Telco Customer Churn dataset. It includes model training, a Flask-based API for predictions, and a live web-based frontend for user interaction.

🎯 Try the live demo:  
👉 [Customer Churn Predictor (GitHub Pages)](https://jajo9147.github.io/Customer-Churn-Prediction/)

## 📦 Project Components

| File/Folder | Description |
|-------------|-------------|
| `churn_prediction_model.ipynb` | Jupyter Notebook for data loading, EDA, preprocessing, model training, and evaluation |
| `app.py` | Flask API that loads the trained model and exposes a `/predict` endpoint |
| `churn_model.joblib` | Saved Scikit-learn logistic regression model |
| `scaler.joblib` | Saved Scikit-learn StandardScaler used during training |
| `inspect_model_features.ipynb` | Helper notebook to verify scaler/model input expectations |
| `docs/index.html` | Interactive HTML frontend deployed via GitHub Pages |
| `requirements.txt` | Python dependencies to run the API |

## 🔧 Technologies Used

- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Backend:** Python, Flask, Flask-CORS
- **Frontend:** HTML, JavaScript
- **Deployment:** GitHub Pages (static site)

## 🚀 How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/jajo9147/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the API server:**
   ```bash
   python app.py
   ```

4. **Test the API:**
   - Endpoint: `http://127.0.0.1:5000/predict`
   - Payload: JSON-formatted feature input matching training order

## 🌐 Live Web Demo

The interactive churn prediction form is available via GitHub Pages:

👉 [https://jajo9147.github.io/Customer-Churn-Prediction/](https://jajo9147.github.io/Customer-Churn-Prediction/)

Users can input real-time customer attributes (e.g., tenure, gender, services used) and receive a churn probability score powered by the trained logistic regression model.

## 📈 Future Enhancements

- Add model explainability (SHAP, feature importance)
- Time-to-churn prediction using survival models
- API hosting on Render or Railway for real-time inference

---

Made by [jajo9147](https://github.com/jajo9147)
