# Food Delivery Time Prediction using Random Forest

## Project Overview
This project focuses on predicting food delivery time using machine learning techniques. The model helps estimate delivery duration based on various factors such as distance, traffic conditions, weather, and order details.

A **Random Forest Regressor** is used to build a robust prediction system that improves delivery efficiency and customer satisfaction.

---

## Objectives
- Predict accurate food delivery time
- Analyze factors affecting delivery delays
- Help businesses optimize logistics and operations

---

## Dataset
- Source: Kaggle (Food Delivery Dataset)
- Features include:
  - Delivery distance
  - Weather conditions
  - Traffic density
  - Order time
  - Delivery location
  - Rider details

---

## Tech Stack
- **Python**
- **Pandas, NumPy** – Data preprocessing
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Model building
- **Random Forest Regressor** – Prediction model

---

## Project Workflow
1. Data Collection & Loading  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Building using Random Forest  
6. Model Evaluation  
7. Prediction & Insights  

---

## Model Details
- Algorithm: **Random Forest Regressor**
- Why Random Forest?
  - Handles non-linear relationships
  - Reduces overfitting
  - Provides high accuracy

---

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Key Insights
- Delivery time increases with distance and traffic congestion  
- Weather conditions significantly impact delivery delays  
- Peak hours lead to longer delivery times  

---

## Results
The Random Forest model achieved strong predictive performance and provided reliable delivery time estimates, making it suitable for real-world applications.

---

## Future Improvements
- Use advanced models like XGBoost or Gradient Boosting  
- Integrate real-time traffic APIs  
- Deploy as a web application  
- Add route optimization features  

---

## 📁 Project Structure
├── data/
├── notebooks/
├── model/
├── app/
├── README.md


---

## 🧑‍💻 Author
Aman Singh  
B.Tech CSE (Data Science)  

---

## ⭐ Acknowledgements
- Kaggle for dataset
- Open-source libraries (Scikit-learn, Pandas, etc.)

---

## 📌 How to Run
```bash
git clone https://github.com/your-username/food-delivery-time-prediction.git
cd food-delivery-time-prediction
pip install -r requirements.txt
python main.py
