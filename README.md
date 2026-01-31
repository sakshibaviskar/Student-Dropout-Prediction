# 🎓 Student Dropout Prediction Using Machine Learning

📂 **Repository:** Student-Dropout-Prediction 

This project is a **group-based Machine Learning mini project** focused on predicting student dropout risk using academic, demographic, and financial data.  
The system helps educational institutions **identify at-risk students early** and provide timely support & intervention.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| **Student_Dropout_Prediction.ipynb** | Complete ML pipeline (EDA → Preprocessing → PCA → Modeling → Evaluation) |
| **Student_Dropout_Prediction_Presentation.pdf** | Final project presentation |
| **student_dropout.csv** | Dataset used for training and testing |

---

## 🔍 Project Highlights

### 📊 Exploratory Data Analysis
- Age distribution  
- Gender vs Target comparison  
- Course-wise analysis  
- Financial indicators  
- Correlation heatmap  

### ⚙️ Data Preprocessing
- Categorical feature encoding  
- Feature scaling  
- Train-test split  
- Outlier handling  

### 📉 Dimensionality Reduction
- Applied **PCA**
- Reduced semester academic features from **12 → 2 components**

---

## 🤖 Machine Learning Models Implemented

- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Decision Tree  
- Random Forest  
- Bagging  
- AdaBoost  
- Gradient Boosting  
- ⭐ **Stacking Ensemble (Best Model)**  

---

## 🏆 Final Model Performance

| Model | ROC-AUC |
|-------|---------|
| ⭐ Stacking Ensemble | **0.928** |

**Why this model?**
- Strong generalization ability  
- Stable predictive performance  
- Highest AUC among all models  

---

## 🛠 Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python |
| Data Handling | Pandas, NumPy |
| Modeling | Scikit-Learn |
| Visualization | Matplotlib, Seaborn |
| Dimensionality Reduction | PCA |

---

## 📌 Conclusion

The system successfully predicts **students at risk of dropping out** with high accuracy.  
It enables institutions to take **proactive actions**, improve retention rates, and support student success.

---

👥 *This project was developed as a group mini-project for academic purposes.*
