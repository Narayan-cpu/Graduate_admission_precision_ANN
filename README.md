# 🎓 Graduate Admission Prediction using Artificial Neural Network (ANN)

Predicting the **Chance of Admit** for graduate programs using a Deep Learning model built with **TensorFlow & Keras**.

---

## 📌 Project Overview

This project uses an **Artificial Neural Network (ANN)** to predict the probability of admission based on academic and profile features like GRE, TOEFL, CGPA, SOP strength, etc.

It is a **regression problem**, where the output is a value between 0 and 1 representing the admission probability.

---

## 📊 Dataset Information

- **Total Samples:** 500
- **Features:** 7
- **Target Variable:** Chance of Admit

### Features Used:

- GRE Score
- TOEFL Score
- University Rating
- SOP
- LOR
- CGPA
- Research

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib

---

## 🔄 Project Workflow

1. Load Dataset
2. Data Cleaning
   - Removed Serial Number column
   - Checked for duplicates
3. Train-Test Split (80-20)
4. Feature Scaling using MinMaxScaler
5. Build ANN Model
6. Train Model (100 epochs)
7. Evaluate using R² Score
8. Visualize Training & Validation Loss

---

## 🧠 Model Architecture

Input Layer: 7 Neurons
Hidden Layer 1: 7 Neurons (ReLU)
Hidden Layer 2: 3 Neurons (ReLU)
Output Layer: 1 Neuron (Linear Activation)

---


- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

---

## 📈 Training Performance

- Epochs: 100
- Validation Loss decreases consistently
- Model trained successfully without overfitting in early stages

---

## 📉 Evaluation

R² Score on Test Data:

-0.53


⚠️ Negative R² indicates the model is not generalizing well on test data.  
Further improvements can include:

- Increasing model complexity
- Hyperparameter tuning
- Adding Dropout
- Feature engineering
- Trying different scaling techniques

---

## 📊 Loss Visualization

Training and validation loss were plotted using Matplotlib to monitor model learning.

---

## 🚀 How to Run

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib

```

Then run the notebook or Python script.

