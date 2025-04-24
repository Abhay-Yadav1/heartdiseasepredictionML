# heartdiseasepredictionML
# **❤️ Heart Disease Prediction Project**  
**🔍 Explore Machine Learning Models to Predict Heart Disease Risk**  

---

## **📌 Overview**  
This project analyzes the **Heart Disease UCI Dataset** to predict cardiovascular risk using **7 powerful ML models**. The dataset includes features like age, cholesterol levels, blood pressure, and more.  

### **🚀 Key Features**  
✅ **Exploratory Data Analysis (EDA)** with insightful visualizations  
✅ **7 ML Models** compared for performance  
✅ **Hyperparameter Tuning** for optimal results  
✅ **Voting Classifier** for ensemble learning  

---

## **📊 Dataset Features**  
| Feature       | Description                          | Relevance to Heart Disease |  
|--------------|-------------------------------------|---------------------------|  
| **Age**      | Patient's age in years              | 🎯 Risk increases with age |  
| **Sex**      | Gender (1 = Male, 0 = Female)       | 🚹 Higher risk in males |  
| **Cp**       | Chest pain type (0-3)               | 💔 Asymptomatic pain = High risk |  
| **Trestbps** | Resting blood pressure (mmHg)       | ⚠️ Hypertension = Risk factor |  
| **Chol**     | Serum cholesterol (mg/dL)           | 🧪 High cholesterol = Higher risk |  
| **Thalach**  | Max heart rate achieved             | ❤️‍🩹 Lower rate = Higher risk |  
| **Oldpeak**  | ST depression (exercise-induced)    | ⚠️ ≥1.0 = Strong risk indicator |  

---

## **🤖 Machine Learning Models Used**  

### **1. Support Vector Classifier (SVC) 🏆**  
- **Kernel:** `linear`  
- **Best for:** High-dimensional data  
- **Accuracy:** ~85%  

### **2. Random Forest 🌲**  
- **Ensemble of decision trees**  
- **Handles non-linear relationships**  
- **Feature importance ranking included**  

### **3. Logistic Regression 📉**  
- **Baseline model**  
- **Interpretable coefficients**  
- **Works well with balanced data**  

### **4. Naive Bayes 🧪**  
- **Fast & lightweight**  
- **Assumes feature independence**  
- **Good for quick prototyping**  

### **5. XGBoost Classifier ⚡**  
- **Gradient boosting** (state-of-the-art)  
- **Auto-handles missing values**  
- **Best accuracy: ~87%**  

### **6. Decision Tree 🌳**  
- **Simple & interpretable**  
- **Prone to overfitting** (used `max_depth=3`)  

### **7. Voting Classifier 🤝**  
- **Combines SVC, RF, XGBoost**  
- **Improves robustness**  

---

## **📈 Performance Comparison**  
| Model               | Accuracy | Precision | Recall | F1-Score |  
|---------------------|----------|-----------|--------|----------|  
| **SVC**             | 85%      | 0.83      | 0.88   | 0.85     |  
| **Random Forest**   | 86%      | 0.84      | 0.89   | 0.86     |  
| **XGBoost**         | 87%      | 0.86      | 0.88   | 0.87     |  
| **Voting Classifier** | **88%** | **0.87**  | **0.90** | **0.88** |  

---

## **🔧 How to Run This Project**  
1️⃣ **Install dependencies**:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```  
2️⃣ **Run Jupyter Notebook**:  
```bash
jupyter notebook heart_disease_prediction.ipynb
```  
3️⃣ **For Kaggle**: Upload the notebook and ensure the dataset is linked.  

---

## **💡 Key Insights**  
🔴 **High-risk groups**:  
- Age > 50  
- Cholesterol > 250 mg/dL  
- ST depression (`oldpeak`) ≥ 1.0  

🟢 **Protective factors**:  
- Higher max heart rate (`thalach`)  
- No exercise-induced angina (`exang=0`)  

---

---

## **🚀 Future Improvements**  
- **Deploy as a web app** (Flask/Streamlit)  
- **Try deep learning** (Neural Networks)  
- **Add SHAP values** for model interpretability  

---

**👨‍💻 Connect with me:**  
[![LinkedIn]([https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/abhay-yadav-508a48289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app))  
[![Kaggle]([https://img.shields.io/badge/Kaggle-Notebook-orange)](https://kaggle.com/yournotebook](https://www.kaggle.com/abhay8471))  

**⭐ Give this repo a star if you found it useful!**  

--- 

Made with ❤️ and Python 🐍
