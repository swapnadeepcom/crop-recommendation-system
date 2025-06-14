# 🌾 Crop Recommendation System

> A machine learning-based tool to suggest the most suitable crop based on soil and environmental factors.  
> **Model Accuracy:** ⭐ 99.32% using Random Forest Classifier.

---

## 📖 Overview

The **Crop Recommendation System** uses machine learning to predict the best crop to grow based on soil nutrients and environmental conditions. By leveraging the power of the **Random Forest Classifier**, it achieves high prediction accuracy, supporting farmers, agronomists, and researchers in making data-driven decisions.

---

## 🎯 Features

- 🌱 **Accurate Crop Prediction**: 99.32% accuracy using Random Forest.
- 📊 **Multi-Parameter Input**: Considers essential soil and climate data.
- 👨‍🌾 **User-Friendly**: Easily integrable into agriculture apps and platforms.

---

## 📥 Input Parameters

| Parameter     | Description                                  |
|---------------|----------------------------------------------|
| `Nitrogen (N)`| Nitrogen content in the soil                 |
| `Phosphorus (P)`| Phosphorus content in the soil              |
| `Potassium (K)`| Potassium content in the soil                |
| `Temperature (°C)`| Average temperature in the area          |
| `Humidity (%)`| Relative environmental humidity              |
| `pH`          | Soil pH value (acidity/alkalinity)           |
| `Rainfall (mm)`| Average rainfall in millimeters             |

---

## 🧰 Technology Stack

- **Language**: Python  
- **Machine Learning Algorithm**: Random Forest Classifier  
- **Libraries Used**:
  - `Scikit-learn`
  - `Pandas`
  - `NumPy`
  - `Matplotlib`
  - `Seaborn`

---

## 📊 Model Performance

- **Accuracy**: `99.32%`  
- **Classifier**: Random Forest  
- Highly reliable for real-world prediction and deployment.

---

## 🧠 Tree Map Visualization

A decision tree map from the Random Forest model visually explains how predictions are made based on input parameters.

> *[Insert Tree Map Image Here — e.g., `static/treemap.png`]*

---

## 📁 Project Structure

Crop-Recommendation/
├── app.py
├── templates/
│ └── index.html
└── static/
└── (images, CSS, JS, etc.)


---

## 🚀 Usage Instructions

1. **Install Required Libraries**:
   ```bash
   pip install scikit-learn pandas numpy matplotlib seaborn

2. Load Dataset:
   Use a dataset with soil and weather parameters.

3. Train Model (Optional):
   Train a new Random Forest model with your dataset if needed.

4. Run the App:
   python app.py

5. Enter Parameters and Get Prediction:
   Use the UI or function to predict the ideal crop based on inputs.

<img src="static/images/Screenshot 2025-06-14 194235.png" alt="UI Screenshot" width="600"/>

## ✅ Conclusion
This Crop Recommendation System offers a powerful, accurate, and scalable solution for modern agriculture. By leveraging machine learning, it helps stakeholders make informed decisions to improve yield, sustainability, and efficiency.

## 📄 License
This project is licensed under the MIT License — see the LICENSE file for details.