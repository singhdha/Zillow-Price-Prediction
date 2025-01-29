# 🏠 Zillow iBuying Analysis & House Price Prediction with MLP

**Predicting Real Estate Prices & Evaluating iBuyer Profitability Using Neural Networks**  
*Inspired by Zillow's Automated Valuation Model (Zestimate) and iBuying Challenges*

---

## 📌 Overview
This project explores house price prediction using multilayer perceptron (MLP) models and evaluates the profitability of the iBuyer business model, inspired by Zillow's Zestimate algorithm and their discontinued iBuying venture, *Zillow Offers*. The analysis connects machine learning predictions to real-world financial outcomes observed in the case study.

---

## 🚀 Key Features  
🔹 **Data Preprocessing**  
- Split training data into training/validation sets.  
- Handle missing values and feature scaling.  

🔹 **MLP Model Architectures**  
- **Base Model**: 2 hidden layers (256, 128 units).  
- **Complex Model**: 4 hidden layers (512, 256, 128, 64 units).  
- **Regularized Model**: 4 hidden layers + dropout layers to prevent overfitting.  

🔹 **Hyperparameter Tuning**  
- Optimize learning rate, batch size, and dropout rates.  
- Track performance using validation errors.  

🔹 **Profit Analysis**  
- Simulate iBuyer profitability using predicted vs. actual prices.  
- Evaluate risks akin to Zillow’s $1.6B loss in iBuying.  

---

## 📊 Deliverables  
1. **Training vs. Validation Error Plots**  
   - Compare performance across model architectures.  
2. **Hyperparameter Tuning Table**  
   - Document best configurations and validation errors.  
3. **iBuyer Profit Analysis Report**  
   - Assess financial viability using Zillow Offers’ case study insights.  

---

## 📂 Case Study Context  
- **Zillow Offers**: Discontinued in 2021 after accumulating $1.6B losses.  
- **Challenges**: Overpriced acquisitions, market volatility, and operational inefficiencies.  
- **Connection**: This project evaluates how accurate price predictions could mitigate such risks.  

---

## ⚙️ Tech Stack  
- **Python 3.x**  
- **TensorFlow/Keras** for MLP implementation.  
- **Pandas/NumPy** for data manipulation.  
- **Matplotlib/Seaborn** for visualizations.  

---
