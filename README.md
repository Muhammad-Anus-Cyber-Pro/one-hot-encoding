# 📊 Feature Engineering: One-Hot Encoding

## 📖 Overview
This project focuses on applying One-Hot Encoding to categorical data.

One-Hot Encoding converts each category into a separate binary column (0 or 1), allowing machine learning models to process categorical variables without assuming any order.

---

## ⚙️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

## 🧠 Concepts Covered
- Feature Engineering  
- Categorical Data Encoding  
- One-Hot Encoding  
- Data Preprocessing  

---

## 🔄 What is One-Hot Encoding?

One-Hot Encoding creates a new binary column for each category.

Example:
Color = [Red, Blue, Green]

Red → [1, 0, 0]
Blue → [0, 1, 0]
Green → [0, 0, 1]


---

## 📊 When to Use One-Hot Encoding?

- When categories have NO natural order  
- Nominal data (e.g., cities, job roles, products)  
- Prevents model from assuming relationships between categories  

---

## ⚠️ Limitation

- Increases number of features (curse of dimensionality)  
- Not efficient for high-cardinality data  

---

## 🚀 Implementation Steps

1. Identified categorical features  
2. Applied One-Hot Encoding  
3. Converted categories into binary columns  
4. Used transformed data for model training  

---
