# 🚀 Heart Disease Risk Prediction Project

## 📋 Project Overview
I recently completed a comprehensive **💖 Heart Disease Risk Prediction** project using the **CDC BRFSS 2015 dataset**, combining advanced machine learning with healthcare analytics to identify early risk factors for cardiovascular diseases. This project demonstrates how data science can empower preventive healthcare through accurate risk assessment.

---

## 🎯 Objective
To predict heart disease using demographic, behavioral, and clinical indicators, enabling early intervention and data-driven preventive healthcare strategies.

---

## ⚙️ Technical Implementation

### Models Compared
- **🧩 LightGBM** | **🧩 XGBoost** | **🧩 Random Forest** | **🧩 Logistic Regression**

### 🏆 Best Performing Model: **LightGBM**
- **ROC-AUC**: 0.8363
- **Recall**: 0.7919  
- **F1-Score**: 0.3788
- **✅ Successfully handled 8.7:1 class imbalance**

---

## 🔍 Key Feature Importance

### Top 10 Most Predictive Features
1. **Any Chronic Disease** 🩺
2. **High Blood Pressure (HighBP)** 💓
3. **General Health (GenHlth)** 📊
4. **Stroke History** 🧠
5. **Sex** 👫
6. **Age Group** 📅
7. **Age** 🎂
8. **High Cholesterol (HighChol)** 🍳
9. **Difficulty Walking (DiffWalk)** 🚶‍♀️
10. **Smoker** 🚬

---

## 📊 Model Interpretability & Insights

### 🧮 Logistic Regression Odds Ratios
- **Poor General Health** → **1.63× increased risk**
- **Age 50+** → **1.51× increased risk** 
- **Male Gender** → **1.49× increased risk**
- **High Cholesterol** → **1.36× increased risk**
- **High Blood Pressure** → **1.32× increased risk**

---

## 👨‍👩‍🦳 Demographic Risk Patterns

### Age & Gender Trends
- **Heart disease risk increases sharply after age 60**
- **Males show consistently higher prevalence**
- **Lower income & education levels correlate with higher risk**

---

## 💪 Lifestyle & Behavioral Insights

### 🚨 Risk Increasing Factors
- **Smoking** ↑
- **Difficulty Walking** ↑  
- **Heavy Alcohol Consumption** ↑

### 🛡️ Protective Factors
- **Physical Activity** ↓ Risk
- **Vegetable & Fruit Consumption** ↓ Risk

---

## 🔗 Correlation Analysis

### Key Relationships
- **💡 Positive Correlation**: Age & Physical Health Issues
- **💡 Negative Correlation**: Education Level & Heart Disease Risk
- **💡 Negative Correlation**: Income Level & Heart Disease Risk

*→ Lifestyle and socioeconomic indicators show strong connections with heart health*

---

## 📈 Model Performance

### Ranking Summary
1. **LightGBM**: ROC-AUC = 0.8363, F1 = 0.3788
2. **Logistic Regression**: ROC-AUC = 0.8356, F1 = 0.3820  
3. **Random Forest**: ROC-AUC = 0.8333, F1 = 0.3773
4. **XGBoost**: ROC-AUC = 0.8237, F1 = 0.3874

*LightGBM and Logistic Regression lead with optimal balance of accuracy and interpretability*

---

## 🌐 Web Application

### 🚀 Flask Heart Disease Risk Predictor
Developed an interactive web application allowing users to assess individual heart disease risk based on key health parameters.

#### 💥 Example Prediction Output:
```
🩺 Risk Level: HIGH RISK (89.2% Probability)
📋 Recommendation: Immediate consultation with healthcare provider recommended.
```

**Access the app at**: `http://127.0.0.1:5000`

---

## 💡 Key Business & Healthcare Insights

### ✅ Critical Success Factors
- **Chronic conditions are the strongest predictors** of heart disease
- **Lifestyle modifications** can significantly impact prevention
- **Machine learning achieves ~84% accuracy** in risk prediction
- **Early detection through AI** enables life-saving interventions

### 🎯 Prevention Strategies
- **Regular health screenings** for high-risk demographics
- **Lifestyle intervention programs** targeting smoking and physical activity
- **Personalized risk assessments** using predictive modeling

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|-------------|
| **Programming** | Python 3.x |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn, LightGBM, XGBoost |
| **Visualization** | Matplotlib, Seaborn |
| **Web Framework** | Flask |
| **Model Interpretation** | SHAP, Odds Ratios |

---

## 🎯 Business Impact

### 🏥 Healthcare Applications
- **Early risk detection** for preventive care
- **Resource allocation** for high-risk populations
- **Personalized treatment plans** based on risk profiles

### 💰 Economic Benefits
- **Reduced healthcare costs** through early intervention
- **Improved patient outcomes** via targeted prevention
- **Data-driven healthcare decisions** optimizing resource utilization

---

## 🔮 Future Enhancements

### Planned Improvements
- **Real-time risk monitoring** integration
- **Mobile application development**
- **Expanded dataset** including genetic markers
- **Integration with electronic health records**

---

## 📞 Conclusion

This project demonstrates the powerful synergy between **artificial intelligence** and **healthcare analytics**, providing a scalable solution for heart disease risk prediction that can save lives through early detection and preventive care.




