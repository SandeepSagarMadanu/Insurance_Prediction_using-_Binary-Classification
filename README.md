# 🏥 Insurance Prediction - Binary Classification

This project focuses on building a binary classification model to predict whether an individual will buy insurance based on various demographic and personal features.

## 📌 Project Overview

- **Goal:** Predict if a customer will purchase insurance (Yes/No) using binary classification.
- **Type:** Supervised Machine Learning
- **Model Type:** Binary Classifier
- **Algorithm(s):** Logistic Regression, Random Forest, Support Vector Machine, etc.
- **Tools Used:** Python, Jupyter Notebook, scikit-learn, pandas, matplotlib, seaborn

---

## 📊 Dataset Information

The dataset used in this project includes the following columns:

- `age`: Age of the individual
- `gender`: Gender of the individual
- `bmi`: Body Mass Index
- `children`: Number of children
- `smoker`: Smoking habit (Yes/No)
- `region`: Residential region
- `charges`: Medical charges billed
- `insurance_bought`: Target variable (1 - Insurance Purchased, 0 - Not Purchased)

> Note: Dataset source is either synthetic or publicly available.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib & Seaborn (EDA & Visualization)**
- **scikit-learn (ML Models & Evaluation)**

---

## 🔍 Project Workflow

1. **Data Loading & Inspection**
2. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
3. **Exploratory Data Analysis (EDA)**
4. **Model Building**
   - Train-test split
   - Training various ML models
5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - ROC-AUC Curve
6. **Model Selection & Conclusion**

---

## ✅ Model Performance

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 89%      | 88%       | 86%    | 87%      |
| Random Forest      | 91%      | 90%       | 88%    | 89%      |
| SVM                | 87%      | 85%       | 83%    | 84%      |

*(These values are placeholders — update them based on your notebook results.)*

---

## 📁 Repository Structure

insurance-prediction/
│
├── insurance_predection_Binary_classification.ipynb # Main Jupyter Notebook
├── README.md # Project overview
├── requirements.txt # (Optional) Required libraries
└── dataset/ # (Optional) Dataset files

## 📌 Future Work

- Hyperparameter tuning
- Deployment as a web app using Flask or Streamlit
- Incorporating more real-world features (occupation, income, etc.)
- Addressing class imbalance using SMOTE or class weights

---

## 🤝 Acknowledgements

Thanks to open-source data providers and contributors to the Python ecosystem.

---

## 📧 Contact

For any queries or suggestions, reach out via GitHub Issues or email.

