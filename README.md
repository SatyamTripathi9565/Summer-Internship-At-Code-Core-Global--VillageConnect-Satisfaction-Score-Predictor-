# Summer-Internship-At-Code-Core-Global--VillageConnect-Satisfaction-Score-Predictor-
A Machine Learning project to predict **Satisfaction Score** for rural services (Electricity, Internet, Water, Healthcare) using the **VillageConnect** dataset.   The model is deployed as an **interactive Streamlit web app** so users can try predictions in real time.
## 🚀 Features
- Data cleaning and preprocessing
- Feature engineering with polynomial features
- One-hot encoding for categorical variables
- Model training with **XGBoost Regressor**
- Hyperparameter tuning using **GridSearchCV**
- Model evaluation with **MSE** and **R² Score**
- Interactive prediction via **Streamlit**
- Correlation heatmap visualization

---

## 📂 Project Structure
├── Week9/
│ ├── app.py # Streamlit app
│ ├── project.py # Model training and evaluation
│ ├── villageconnect_large.csv # Dataset
│ ├── village_model_best.pkl # Saved trained model
│ ├── Screenshot.png # Demo screenshot
└── README.md


---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your name>/villageconnect-predictor.git
cd villageconnect-predictor/Week9

2️⃣ Install dependencies
pip install -r requirements.txt

requirements.txt
pandas
numpy
scikit-learn
xgboost
seaborn
matplotlib
streamlit

3️⃣ Run the Streamlit App Locally
streamlit run app.py

📊 Model Performance
| Metric   | Value |
| -------- | ----- |
| Test MSE | 0.73  |
| R² Score | 0.003 |





