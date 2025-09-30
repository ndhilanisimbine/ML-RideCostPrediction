# Predicting Ride Cost with Machine Learning

This project explores predicting ride cost using two different models: Linear Regression and Random Forest Regressor. It compares performance using metrics such as Mean Squared Error (MSE) and R² Score.

## 📊 Objective
To understand what factors most influence ride pricing and evaluate which regression model performs better.

## 🧠 Models Used
- Linear Regression
- Random Forest Regressor

## 🧪 Evaluation
| Model               | Mean Squared Error | R² Score |
|---------------------|-------------------|----------|
| Linear Regression   | 78.74              | 0.009    |
| Random Forest (50 trees, depth=10) | 72.16     | 0.092    |

## 🔍 Feature Importance
The Random Forest model identified the following as most influential:
- Driver Ratings
- Ride Distance
- Customer Rating
- Booking Value


## 📁 Project Structure
- `notebooks/`: Jupyter notebook with model training & evaluation
- `images/`: Output visualizations
- `data/`: Dataset (or instructions if private)
- `requirements.txt`: Python dependencies

## ✅ How to Run
1. Clone the repo
2. Install packages:


3. Open the notebook and run cell by cell

## 📌 Next Steps
- Try other models (e.g. Gradient Boosting, XGBoost)
- Tune hyperparameters
- Add Streamlit dashboard to make it interactive

---

Want to give feedback or collaborate? Open a PR or drop me a message.
