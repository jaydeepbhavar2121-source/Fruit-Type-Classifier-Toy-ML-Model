# Fruit-Type-Classifier-Toy-ML-Model
A beginner-friendly machine learning project in Google Colab that classifies fruits based on color, size, and weight using a decision tree classifier.

# 🍎 Fruit Classifier ML Model

This is a beginner-friendly **machine learning project** built in **Google Colab**.  
The model classifies fruits as either **Apple** or **Banana** based on **color**, **size**, and **weight** using a Decision Tree Classifier.

---

## 📂 Project Structure
fruit-classifier-ml/
│── simple_fruit_dataset.csv # Dataset used for training
│── fruit_classifier.ipynb # Google Colab notebook with ML code
│── README.md # Project documentation



---

## 🚀 Features
- Simple, clean dataset for easy understanding
- Encodes text into numerical format for ML
- Trains a Decision Tree Classifier using `scikit-learn`
- Predicts fruit type from user-provided inputs

---

## 📊 Dataset
The dataset contains:
- **Color** — Categorical (Red, Green, Yellow)
- **Size_cm** — Size of the fruit in centimeters
- **Weight_g** — Weight of the fruit in grams
- **Fruit** — Target label (Apple or Banana)

---

## 🛠 Technologies Used
- Python 3
- Pandas
- scikit-learn
- Google Colab

---

## 📖 How to Run the Project
1. Open `fruit_classifier.ipynb` in **Google Colab**
2. Upload `simple_fruit_dataset.csv` when prompted
3. Run all cells to train the model
4. Try predictions with custom values

---

## 🔮 Example Prediction
```python
# Example: Color=Red (encoded as 2), Size=8 cm, Weight=160 g
prediction = model.predict([[2, 8, 160]])
print("Predicted Fruit:", fruit_encoder.inverse_transform(prediction)[0])


 ## License
This project is licensed under the MIT License — you are free to use, modify, and share it.
