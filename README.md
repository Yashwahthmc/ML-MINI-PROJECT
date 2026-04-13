# 🌌 Planetary Data Anomaly Detection using Random Forest

## 📌 Overview

This project focuses on detecting anomalies in planetary data using a **Random Forest Machine Learning model**. The system analyzes key environmental features such as temperature, pressure, and radiation to classify whether a given data point represents **normal conditions or an anomaly**.

This project simulates real-world planetary monitoring systems where detecting abnormal patterns is crucial for early warnings and scientific analysis.

---

## 🎯 Objective

* Build a machine learning model for anomaly detection
* Classify planetary conditions as **Normal (0)** or **Anomaly (1)**
* Handle large-scale data efficiently
* Implement real-time anomaly detection

---

## 🧠 Algorithm Used

* **Random Forest Classifier**

  * Ensemble learning method
  * Combines multiple decision trees
  * Reduces overfitting
  * Provides high accuracy and robustness

---

## 📊 Dataset Details

| Feature     | Description                |
| ----------- | -------------------------- |
| Temperature | Planet surface temperature |
| Pressure    | Atmospheric pressure       |
| Radiation   | Radiation levels           |
| Label       | 0 = Normal, 1 = Anomaly    |

* Dataset Type: **Synthetic**
* Total Samples: **6000**
* Data Format: **Tabular**

---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

## 🚀 Project Workflow

1. Data Generation (Synthetic dataset)
2. Data Preprocessing
3. Train-Test Split
4. Model Training using Random Forest
5. Model Evaluation
6. Real-Time Prediction Simulation
7. Feature Importance Analysis

---

## 📈 Results

* **Accuracy:** 99.75%
* **Confusion Matrix:**

  ```
  [[1003    1]
   [   2  194]]
  ```

### 📊 Interpretation

* High accuracy achieved with realistic noisy data
* Very low misclassification
* Model successfully detects anomalies

---

## 🔍 Feature Importance

* Radiation → Highest impact
* Temperature → Moderate impact
* Pressure → Least impact

---

## ⚡ Real-Time Simulation

The model can predict new incoming data dynamically:

**Example:**

```
Input: [45, 60, 130]
Output: Anomaly Detected
```

---

## 📸 Sample Outputs

* Dataset visualization
* Confusion matrix
* Feature importance graph
* Real-time predictions

---

## 🔮 Future Enhancements

* Use real-world datasets (e.g., NASA data)
* Implement deep learning models
* Develop a web-based dashboard
* Integrate IoT-based data collection

---

## 📂 Project Structure

```
Planetary_Anomaly_Project/
│── code/
│── dataset/
│── report/
│── ppt/
│── README.md
```

---

## 📚 References

1. Ethem Alpaydın – Introduction to Machine Learning
2. Scikit-learn Documentation
3. Python Documentation
4. Kaggle Datasets
5. Research papers on Random Forest

---

## 👨‍💻 Author

* Name: [Your Name]
* Register Number: [Your Reg No]
* Course: B.Tech AI & DS

---

## ⭐ Conclusion

This project demonstrates how machine learning can be effectively used for anomaly detection in planetary data. The Random Forest model provides high accuracy and reliable performance, making it suitable for real-world applications.

---
