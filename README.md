# Customer Churn Prediction with a Live Web API and Deployed Frontend

This project demonstrates a complete end-to-end machine learning workflow using the Telco Customer Churn dataset. It includes model training, a Flask-based API for predictions, and a live web-based frontend for user interaction.

🎯 Try the live demo:  
👉 [Customer Churn Predictor (GitHub Pages)](https://jajo9147.github.io/Customer-Churn-Prediction/)

---

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

---

## 🔧 Technologies Used

- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Backend:** Python, Flask, Flask-CORS
- **Frontend:** HTML, JavaScript
- **Deployment:** GitHub Pages (static site)

---

## 🚀 How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/jajo9147/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
