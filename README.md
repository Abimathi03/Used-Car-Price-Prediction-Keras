# 🚗 Used Car Price Prediction using Keras

This project predicts the selling prices of used cars using a deep learning regression model built with **Keras**. The model is trained on structured automotive data with features such as brand, year, mileage, fuel type, engine capacity, and transmission type.

---

## 📌 Problem Statement

Given various features of a car, the goal is to predict its **market resale price** using a neural network model. This is a supervised regression problem useful in the automotive resale and recommendation industries.

---

## 📊 Dataset

The dataset includes the following key features:
- `Brand`
- `Model`
- `Year`
- `Mileage`
- `Fuel Type`
- `Transmission`
- `Engine Capacity`
- `Price` (Target variable)

> 📁 File used: `used_cars.csv`

---

## 🧠 Model Architecture

- **Input Layer**: Preprocessed numerical + one-hot encoded categorical features
- **Hidden Layers**:
  - Dense(128) + ReLU
  - Dense(64) + ReLU
- **Output Layer**: Dense(1) for regression

- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- **Epochs**: 50
- **Batch Size**: 32

---

## 📈 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

---

## 📉 Visualizations

- Training vs. Validation Loss curve
- Actual vs. Predicted Car Price scatter plot

---

## 🛠️ How to Run

1. Open the notebook
2. Open the file
3. Run the Cells

---

## 📚 Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Keras (TensorFlow backend)
  
---

# ✅ Results

The model was able to accurately estimate used car prices and showed promising results, validated by low error values and good fit between actual and predicted values.
