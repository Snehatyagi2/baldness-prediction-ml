# 🧬 Baldness Prediction using Machine Learning

## 📌 Overview
This project explores how genetic, hormonal, and lifestyle factors influence baldness (androgenetic alopecia) using machine learning.

A synthetic dataset was created based on biological insights, and models were trained to predict baldness severity.

---

## 🚀 Features
- Synthetic dataset based on biological reasoning  
- Feature engineering (Lifestyle Score, Bio Risk)  
- Machine Learning models:
  - Logistic Regression  
  - Random Forest  
- Prediction system  

---

## 🧪 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📊 Visualization

### Correlation Heatmap
![Correlation Heatmap](images/heatmap.png)

---

## 🔮 Example Prediction

**Input:**
- Age: 35  
- Family History: Yes  
- Stress: Moderate  
- Sleep: Good  

**Output:**
👉 Moderate Baldness  

---

## 🧠 Key Insights
- Genetic factors are the strongest predictors  
- DHT levels significantly influence baldness  
- Age increases risk  
- Lifestyle factors modify severity  

---

## ⚙️ How It Works

A simplified risk model was used to generate the dataset:
Risk Score =
0.03 × Age

0.5 × Genetic_Risk
0.02 × DHT_Level
0.2 × Family_History
0.1 × Stress
− 0.1 × Sleep
− 0.1 × Diet
---

## 📚 References

These sources were used to guide the biological assumptions in the dataset:

- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5308812/  
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2929555/  
- https://www.nature.com/articles/ncomms10815  
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4387693/  
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5315033/  



Machine learning models then learned patterns from this data.

---

## 📁 Project Structure
baldness-prediction-ml/
│
├── notebook.ipynb
├── README.md
└── images/
└── heatmap.png
---

---

## ⚠️ Disclaimer
This project uses a synthetic dataset and is for educational purposes only.  
It should not be used for medical decisions.

---

## 🌐 Kaggle Notebook
(https://www.kaggle.com/code/snehaatyagi2/notebook5faac48c22)
