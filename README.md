# 🎓 Student Score Prediction Model

This repository contains a Machine Learning model that predicts student scores based on input features such as study hours. The model has been trained and saved in `.pkl` format for reuse and deployment.

## 👥 Project Team
- Dipali Gantait
- Sudipta Singha
- Riyajul Saha

## 📁 Project Contents

- `score_prediction_model.pkl` – Trained ML model saved using `pickle`.
- `README.md` – Overview and instructions.
- `Hours_Scores.csv` – Dataset

## 🧠 Model Information

- **Model Type**: Linear Regression
- **Purpose**: Predict student's score.
- **Input Features**: Study Hours
- **Output**: Predicted Score

## 🧪 How to Use the Model

1. Clone this repository:
   ```bash
   git clone https://github.com/trio-rds-tensors/Score_Prediction_Model.git

2. Install required libraries:
   ```bash
   pip install numpy pandas scikit-learn
3. Load and use the model:
   ```bash
   import pickle
   # Load model
   with open('score_prediction_model.pkl','rb') as file:
      model = pickle.load(file)
   #Predict (example)
   predicted_score=model.predict([[study_hours]])
   print(predicted_score)

## ✅ Example
   ```bash
   # Predict score for 5 study hours
   model.predict([[5]])  # Output [predicted_score]
```
## 📊 Performance
**Accuracy Metric:** R² Score = 0.9678055545167994

The model has been evaluated on test data and performs well on predicting continuous score values.

## 📜 License
This project is open-source and free to use for educational purposes.


