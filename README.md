# 🏷️ Insurance Claim Prediction

## 📌 Project Overview

This project aims to build a **predictive model** that helps insurance companies identify customers who are likely to buy insurance products. By leveraging machine learning algorithms, the model enhances marketing strategies and customer targeting to improve conversion rates.

---

## 🎯 Objective

- Predict whether a customer will purchase an insurance product based on their demographic and historical data.
- Assist the insurance marketing team in **targeting potential customers effectively**.

---

## 🗂️ Dataset

- **Source:** Provided dataset (`train.csv`)
- **Shape:** 595,211 rows × 59 columns
- **Target Variable:** `target` (binary: 0 – will not buy, 1 – will buy)

---

## 🔧 Techniques and Workflow

1. **Data Preprocessing**
   - Checked for null values
   - Performed data scaling using `StandardScaler`

2. **Dimensionality Reduction**
   - Applied **Principal Component Analysis (PCA)** to reduce features from 59 to 45 while retaining maximum variance

3. **Data Balancing**
   - Used **SMOTE (Synthetic Minority Oversampling Technique)** to handle class imbalance in the target variable

4. **Model Building**
   - Built classification models using **scikit-learn**
   - Evaluated model performance using accuracy and classification reports

5. **Suggestions**
   - Provided insights for the insurance marketing team to improve customer purchase rates

---

## 🛠️ Libraries Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## 🚀 How to Run

1. **Clone the repository:**

   git clone https://github.com/yourusername/insurance-claim-prediction.git

   cd insurance-claim-prediction

3. **Install dependencies:**

   pip install -r requirements.txt

4. **Run the Jupyter Notebook:**

   jupyter notebook Insuranceclaim-Final.ipynb

## 📈 Results
Successfully built and evaluated a classification model capable of predicting the likelihood of insurance purchase with satisfactory performance metrics after data balancing and dimensionality reduction.

## 💡 Future Scope
- Implementing advanced algorithms such as XGBoost and LightGBM for improved accuracy.

- Building an interactive dashboard for marketing teams to visualize predictive outcomes.

## 👤 Author
Prashant Kadam

- LinkedIn : www.linkedin.com/in/prashant-kadam-2759122ab

- GitHub : https://github.com/Prashantkadam9146
