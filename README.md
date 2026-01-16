# Flight Price Prediction – Project Report

**Objective**  
Flight Price Prediction using Machine Learning. Includes data preprocessing, feature engineering, and model building to predict flight ticket prices with high accuracy.

---

### 📊 Dataset  
- Features: Airline, Source, Total_Stops, Duration, Route, Destination, Additional_Info  
- Target: Price  

---

### ⚙️ Preprocessing  
- Converted Duration → minutes  
- Extracted Departure/Arrival hours  
- Encoded categorical features (Airline, Source, Destination, Stops)  
- Scaled numerical values  

---

### 🔍 EDA Highlights  
- Non-stop flights are costliest  
- Airline strongly affects price  
- Duration and Stops are major predictors  

---

### 🤖 Models Tried  
- Linear Regression (baseline)  
- Decision Tree, KNN  
- Random Forest ✅ (best)  
- Gradient Boosting (good but slower)  

---

### 📈 Results  
- **Random Forest Regressor** → Best accuracy (highest R², lowest RMSE)  
- Gradient Boosting close second  

---

### 📝 Insights  
- Fewer stops → higher prices  
- Some airlines consistently more expensive  
- Flight duration correlates with price  

--- 

---

**Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  
