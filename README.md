# 🚗 Car Price Prediction using Machine Learning  

## 📌 Project Overview  
This project focuses on predicting the **selling price of cars** using various features such as brand, year, mileage, fuel type, transmission, and more.  
By applying machine learning techniques, the model helps both buyers and sellers estimate fair market prices.  

---

## 📊 Key Steps in the Project  
1. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Encoded categorical variables  
   - Removed duplicates  
   - Created new features like *Car Age*  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution analysis of selling prices  
   - Scatter plots for price relationships  
   - Correlation heatmap to identify key factors  

3. **Model Building**  
   - **Linear Regression** (baseline model)  
   - **Decision Tree Regressor**  
   - **Random Forest Regressor**  

4. **Model Evaluation**  
   Models were compared using R², MSE, and RMSE scores.  

---

## 📈 Results  

| Model                | R² Score | MSE       | RMSE  |  
|-----------------------|----------|-----------|-------|  
| Linear Regression     | 0.75     | 210000    | 458   |  
| Decision Tree         | 0.82     | 180000    | 424   |  
| Random Forest         | 0.89     | 120000    | 346   |  

✅ **Random Forest Regressor** performed the best with the highest accuracy and lowest error.  

---

## 📌 Conclusion & Insights  
- The Random Forest model is the most reliable for car price prediction.  
- This model can assist:  
  - **Buyers** → estimate fair prices before purchase.  
  - **Sellers/Dealers** → set competitive prices.  
- Accuracy can be further improved with additional features such as service history, accident records, and brand reputation.  

---

## 🚀 Future Work  
- Experiment with **XGBoost / Gradient Boosting**  
- Deploy as a **web application** for real-time predictions  
- Train on larger datasets for improved performance  

---

## ⚖️ License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 👤 Author  
- **Sameen J**  
- *Created with Google Colab & Python*  
