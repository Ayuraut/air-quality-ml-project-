# 🌫️ Air Quality Health Impact Prediction using Decision Tree

This project analyzes air quality parameters and predicts the health impact category using a Decision Tree classification model. The system helps understand how pollution levels influence public health risks.

---

## 📌 Problem Statement
Poor air quality has serious health implications. This project aims to classify the level of health impact based on air pollution indicators such as AQI, PM2.5, NO2, SO2, O3, and PM10.

---

## 📊 Dataset Details
- File: `air_quality_health_impact_data1.csv`
- Records: 1799
- Features include:
  - AQI
  - PM2.5, PM10
  - NO2, SO2, O3
  - Temperature, Humidity, Wind Speed
- Target Variable:
  - `HealthImpactClass` (0–3)

---

## 🧠 Machine Learning Approach
- Algorithm Used: **Decision Tree Classifier**
- Data preprocessing:
  - Missing value check
  - Feature selection
  - Standardization using StandardScaler
- Train-Test Split: **70% Training, 30% Testing**

---

## 📈 Exploratory Data Analysis
- Correlation heatmap between air quality parameters
- Bar charts showing mean pollutant levels per health impact class
- Confusion matrix visualization using heatmap

---

## 🧪 Model Evaluation Metrics
- Accuracy
- Precision (weighted)
- Recall (weighted)
- F1 Score

### ✅ Best Accuracy Achieved:

---

## 🌳 Decision Tree Visualization
- Full decision tree plotted using Graphviz
- Tree pruning performed using `max_depth`
- Optimal depth observed at `max_depth = 5`

---

## 🔍 Sample Prediction
The trained model was tested on unseen data and successfully predicted the health impact category with proper class mapping.

---

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz

---

## ▶️ How to Run
1. Clone the repository
2. Install dependencies using `requirements.txt`
3. Open the notebook from the `notebook` folder
4. Run all cells sequentially

---

## 🚀 Future Enhancements
- Try ensemble models like Random Forest
- Add real-time AQI data
- Deploy using Streamlit or Flask

---
