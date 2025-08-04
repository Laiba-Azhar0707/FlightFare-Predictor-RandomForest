# ✈️ FlightFare-Predictor-RandomForest

A machine learning project that predicts airline ticket prices based on various flight and booking features. This project uses the Random Forest Regressor algorithm to analyze and forecast airfare trends for flights between Indian cities.

---

## 📊 Dataset Overview

The dataset consists of real-world flight booking data scraped from a popular travel website. It includes detailed flight features such as:

- **Airline** (e.g., IndiGo, Vistara, AirAsia)
- **Source & Destination Cities**
- **Departure & Arrival Time Categories**
- **Class** (Economy or Business)
- **Number of Stops**
- **Flight Duration**
- **Days Left Before Departure**
- **Ticket Price** (Target variable)

📁 File used: `cleaned_airline_flight_data.csv`  
🔢 Rows: 10,000+  
📌 Target: `Price`

---

## 💡 Project Goals

- Analyze how various factors (Airline, Class, Time, Duration, etc.) affect airfare prices
- Build a machine learning model to predict flight prices
- Visualize and interpret important trends and features

---

## 🤖 ML Model Used

**Random Forest Regressor** (from `sklearn.ensemble`)

- Handles both numerical and categorical data
- Captures non-linear feature interactions
- Provides feature importance insights
- Robust to outliers and overfitting

---

## 🧰 Tech Stack

- `Python 3.x`
- `Pandas` for data handling
- `Matplotlib` & `Seaborn` for visualization
- `Scikit-learn` for ML model
- `Jupyter Notebook` or `.py` script

---

## 📈 Features Engineering & Preprocessing

- Dropped irrelevant columns (e.g., `Flight`, Index)
- Applied One-Hot Encoding to categorical features
- No scaling required for tree-based models
- Split data into training and testing (80/20)

---

## 🧪 Evaluation Metrics

- **RMSE** (Root Mean Squared Error)
- **R² Score**
- **Feature Importances**

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/Laiba-Azhar0707/FlightFare-Predictor-RandomForest.git
cd FlightFare-Predictor-RandomForest

# Install dependencies
pip install -r requirements.txt

# Run the notebook or Python script
jupyter notebook FlightFarePrediction.ipynb
