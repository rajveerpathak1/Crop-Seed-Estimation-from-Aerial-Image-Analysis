# 🌾 Crop Yield Prediction Using Machine Learning

This project predicts crop yield (in Quintals/acre) using environmental and nutrient-based features like rainfall, temperature, and macronutrients (NPK). The goal is to understand which factors most affect yield and build accurate models.

## 📊 Dataset
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/yaminh/crop-yield-prediction)
- **Features:** Rainfall, Temperature, Fertilizer, Nitrogen, Phosphorous, Potassium

## 🔧 Workflow

1. **Data Cleaning**
   - Handled invalid values (e.g., `':'` in temperature)
   - Converted columns to correct data types
   - Handled missing values using median imputation

2. **Exploratory Data Analysis**
   - Histograms for all features (bimodal patterns hinting at two crop types)
   - Scatter plots to examine yield relationships
   - Correlation heatmap
   - Hypotheses: Two crop types (e.g., Rabi and Kharif) supported by clustering

3. **Model Building**
   - **Decision Tree Regressor** (R² ~0.77)
   - **Random Forest Regressor** (R² ~0.80, best model ✅)
   - **Hyperparameter tuning** using GridSearchCV

4. **Evaluation**
   - MAE, MSE, RMSE
   - Distribution plots of actual vs predicted values
   - Feature importance plots

## 📌 Key Insight
> Temperature and rainfall are the most critical predictors of yield. Nutrients like Potassium have lower impact than expected.

## 🔮 Future Improvements
- Introduce soil pH and type if available
- Use ensemble models like XGBoost or SVR for comparison

## 💻 Tech Stack
- Python, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📸 Preview
*(Insert EDA and model result screenshots if using GitHub)*

---

## 📬 Contact
**Rajveer Pathak**  
📧 [tarupa123@gmail.com](mailto:tarupa123@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/rajveerpathak/) | [GitHub](https://github.com/rajveerpathak1)
