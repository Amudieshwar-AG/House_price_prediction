# 🏠 House Price Prediction using Naive Bayes

---

## 📘 Overview  
This mini-project applies **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques to predict the **price category of houses** using the **Naive Bayes algorithm**.  
It classifies homes into **Low**, **Medium**, or **High** price ranges based on key features such as **area, number of rooms, and furnishing type**.

---

## 🧠 Objective  
To develop an **AI model** that learns from historical housing data and predicts the **price range for new properties** using **probabilistic reasoning**.

---

## ⚙️ Algorithm Used — Naive Bayes Classifier  

### 📖 About the Algorithm  
- Based on **Bayes’ Theorem**  
- Assumes **independence** among features  
- Simple, fast, and effective for **categorical and small datasets**  
- Ideal for **classification** tasks like price category prediction  

### 🔢 Formula  
\[
P(Class|Features) = \frac{P(Features|Class) \times P(Class)}{P(Features)}
\]

---

## 📊 Datasets Used  

| File Name | Description |
|------------|-------------|
| **house_data.csv** | Training dataset containing historical house features and their price categories. |
| **new_houses.csv** | Testing dataset with new house details for prediction. |

**Key Columns:**  
`Area`, `Bedrooms`, `Bathrooms`, `Stories`, `Parking`, `Furnishing`, `Price_Category`

---

## 🚀 How the Model Works  

1. The model is trained on data from **house_data.csv**.  
2. It learns patterns between house features and their price categories.  
3. It predicts the **price category** and **approximate price range** for each house in `new_houses.csv`.  

### 🧾 Example Output  

| Area | Bedrooms | Bathrooms | Furnishing | Predicted_Category | Approx_Price_Range |
|------|-----------|------------|-------------|--------------------|--------------------|
| 1500 | 3 | 2 | Semi-Furnished | Medium | ₹40–80 Lakhs |
| 2000 | 3 | 2 | Furnished | High | ₹80 Lakhs–₹1.5 Crore |

---

## 🧩 Project Files  

| File Name | Description |
|------------|-------------|
| **house_prediction_project.ipynb** | Main Jupyter Notebook with training, testing, and visualization code. |
| **house_data.csv** | Training dataset. |
| **new_houses.csv** | Testing dataset. |
| **Screenshot 2025-10-28 183949.png** | Model accuracy output screenshot. |
| **Screenshot 2025-10-28 184032.png** | Predicted results screenshot. |

---

## 🖼️ Output Screenshots  

### ✅ Model Accuracy Output  
![Model Accuracy](./Screenshot%202025-10-28%20183949.png)

### 📈 Prediction Results  
![Prediction Results](./Screenshot%202025-10-28%20184032.png)

---

## 🧰 Tech Stack  

| Component | Description |
|------------|-------------|
| **Language** | Python |
| **Libraries** | Pandas, NumPy, Scikit-learn, Matplotlib |
| **Platform** | Google Colab / Jupyter Notebook |
| **Algorithm** | Gaussian Naive Bayes |

---

## 🎯 Expected Outcome  
- Predicts **Low / Medium / High** price category  
- Displays **approximate cost range (₹20L–₹1.5Cr)**  
- Demonstrates **AI-based decision-making** using probabilistic learning  

---

## 📄 Conclusion  
This project demonstrates how the **Naive Bayes algorithm** can be applied to **real estate price prediction** using AI.  
It offers a **fast, interpretable, and reliable** method for predicting property prices based on numerical and categorical data features.  

---

## 👩‍💻 Author  
**Project by:** *Amudieshwar A G*  
**Subject:** *Artificial Intelligence*  
**Domain:** *AI & Data Science*

---
