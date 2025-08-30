# Thyroid-cancer-detection
Machine Learning project to predict Thyroid Cancer Recurrence using patient medical data.

# 🧬 Thyroid Cancer Recurrence Prediction

This project predicts the **recurrence of Thyroid Cancer** using patient data and machine learning models.  
Built as part of a research & academic project, it explores multiple ML algorithms and compares their performance.

---

## 📂 Project Overview
- **Objective**: Predict whether a Thyroid Cancer survivor’s cancer will reoccur.  
- **Dataset**: Patient medical records including age, gender, smoking history, radiotherapy, pathology, TNM staging, and more:contentReference[oaicite:2]{index=2}.  
- **Goal**: Build and evaluate ML models to provide accurate recurrence predictions.

---

## 📊 Dataset
The dataset contains **383 patient records** with the following features:

- **Demographics**: Age, Gender, Smoking History  
- **Medical History**: Radiotherapy, Physical Examination, Adenopathy  
- **Cancer Characteristics**: Pathology, Focality, Risk, Tumor (T), Node (N), Metastasis (M), Stage  
- **Treatment & Outcomes**: Response to treatment, Recurrence status  

Target Variable: **`Recurred`** → *Yes/No (0/1)*

---

## 🛠️ Technologies Used
- **Python, Pandas, NumPy**
- **Matplotlib & Seaborn** (visualization)
- **Scikit-learn** (ML models)
- **Google Colab / Jupyter Notebook**

---

## 🔍 Exploratory Data Analysis (EDA)
- Age distribution of patients
- Class imbalance in recurrence cases
- Correlation heatmaps for medical features
- Relationship of Thyroid Function & Recurrence

---

## 🤖 Machine Learning Models Tested
We trained & evaluated multiple models:

| Model                | Accuracy |
|-----------------------|----------|
| 🌲 Random Forest      | **98.7%** |
| 🌟 Gradient Boosting  | 97.4% |
| ⚡ AdaBoost           | 96.1% |
| 🧠 MLP Classifier     | 96.1% |
| 📉 Logistic Regression| 93.5% |
| 🌳 Decision Tree      | 90.9% |
| 📊 Gaussian NB        | 88.3% |
| 🔗 KNN                | 85.7% |
| 📈 SVM                | 83.1% |

✅ **Best Model:** **Random Forest Classifier (98.7% accuracy)**

---

## 📌 Key Results
- **Feature Importance (Random Forest):**
  - Most influential: Response, Risk, Tumor stage (T), Node status (N), Age  
- **Confusion Matrix & Classification Reports** confirm Random Forest outperforms others.  

---

## 📂 Files in this Repo
- `dataset.csv` → Patient dataset  
- `ProjectThyroidcancer.ipynb` → Jupyter Notebook with full code  
- `report.pdf` → Detailed report of methodology & findings  
- `README.md` → Project documentation  

---

## 🚀 How to Run
 Clone this repo  
   ```bash
   git clone https://github.com/your-username/Thyroid-cancer-detection.git
   cd thyroid-cancer-detection


