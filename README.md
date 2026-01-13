# 🎓 Student Depression Prediction 🧠📊

## 📌 Project Overview  
This project aims to predict whether a student is likely to experience depression based on academic and lifestyle-related factors.  
I experimented with multiple classification algorithms and compared their performance to understand which model works best.

---

## 📊 Dataset Characteristics  
- **Total Samples:** ~100,000 students  
- **Features:** 11 input features
- **Target Variable:** Depression (Binary: 0 = False, 1 = True)  
- **Class Distribution:** Imbalanced  

---

## 🤖 Models Used  
- Decision Tree  
- Random Forest( **Best Performing Model:**✅)
- XGBoost  

---

## 📈 Results  
- **Accuracy:** ~73%  
- **Recall (Depression):** ~64%  

🔍 **Why Recall Matters?**  
Recall was prioritized because correctly identifying students with depression is more important than overall accuracy in mental health–related problems.

---

## 🧠 Key Learnings  
- How different classification algorithms perform on the same dataset  
- Handling imbalanced data using `class_weight`  
- Importance of recall in sensitive classification problems  
- Feature selection improves model efficiency and interpretability  

---

## 🧪 How to Use  
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Run the cells step-by-step to train and evaluate the models  

---

## 🧰 Tech Stack  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Dataset  
The dataset is included inside the project directory.

---
