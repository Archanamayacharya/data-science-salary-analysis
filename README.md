# data-science-salary-analysis
Exploratory analysis and salary prediction for Data Science roles

# Data Science Salary Analysis & Prediction

## 📌 Overview
This project analyzes global data science salaries to uncover trends, key salary drivers, and predictive insights using machine learning. An interactive Streamlit dashboard was also developed to visualize trends.

📊 Dataset Size: 607 records × 12 columns

👩‍💻 Author: Archana Anil Mayacharya

---

## ✅ Problem Statement
Analyze and model data science job salaries to:
- Identify major salary drivers
- Understand trends by experience, location, company size, and remote work
- Predict salaries using machine learning

---

## 🛠 Tools & Technologies
- **Python**
- **Google Colab**
- **Pandas, NumPy**
- **Matplotlib, Seaborn, Plotly**
- **Scikit-Learn**
- **Statsmodels**
- **Power BI**
- **Streamlit (Deployment)**

---

## 🔄 Process
### 1. Data Cleaning
- Removed duplicates and unnecessary columns
- Converted categorical features to category dtype
- Handled outliers (retained valid high-paying roles)

### 2. Feature Engineering
- Encoded experience level & company size
- Created interaction features (experience × company size, experience × remote)
- One-hot encoded job categories, geography, and work type
- Log-transformed target salary

### 3. Exploratory Data Analysis
- Salary vs Experience Level
- Salary vs Remote Work
- Salary vs Company Size
- Geography-based salary comparison
- Yearly salary trends (2020–2022)
- Correlation heatmap

### 4. Modeling
Models evaluated:
- Linear Regression
- Ridge & Lasso
- Decision Tree
- Random Forest
- Gradient Boosting ✅ (Best)

---

## 📈 Results
- Salary increases strongly with experience (EX > SE > MI > EN)
- Location is the strongest salary driver (US highest)
- Fully remote roles show slightly higher median pay
- Larger companies generally pay more

**Best Model Performance:**
- Gradient Boosting  
- R² ≈ 0.50  
- MAE ≈ $28,336  

---

## 📊 Dashboard
An interactive Streamlit dashboard visualizes:
- Salary by country & experience
- Salary vs remote ratio
- Trends over time

🔗 Live App:  
https://salary-dashboard-hsat6hnqujrh27jegr2jq7.streamlit.app/

---

## 💡 Key Takeaways
- Geography, experience, and company size drive salary
- Remote work benefits senior professionals the most
- ML models can provide meaningful salary predictions

---

## 🚀 Future Improvements
- Add skill-based & industry features
- Improve prediction accuracy
- Build salary prediction simulator
