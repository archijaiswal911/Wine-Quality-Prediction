# 🍷 Wine Quality Prediction using Random Forest

**Project:** Machine Learning model to predict wine quality  
**Author(s):** Archi Jaiswal & Team  
**Institute:** SRM Institute of Science & Technology — Delhi NCR Campus

---

## 📌 Overview
This project predicts the quality of wine based on physicochemical features using a **Random Forest Classifier**. The dataset is taken from the **UCI Machine Learning Repository** and contains attributes such as acidity, sugar, chlorides, sulphates, alcohol, etc.

The goal is to classify wines into quality categories and evaluate model performance.

---

## 🧠 Methodology
1. **Data Collection** — Red wine quality dataset (`winequality-red.csv`) from UCI.
2. **Data Preprocessing**  
   - Handle missing values  
   - Feature scaling (if required)  
   - Splitting dataset into training and testing sets
3. **Model Building** — Train a Random Forest Classifier with tuned hyperparameters.
4. **Evaluation** — Accuracy, Confusion Matrix, Classification Report.

---

## 🛠 Tech Stack
- **Language:** Python 3
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Platform:** Google Colab / Jupyter Notebook

---

## 📊 Sample Results
- **Model Accuracy:** ~90% (varies depending on split & parameters)
- **Insights:** Alcohol and sulphates have strong correlation with wine quality.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Wine-Quality-Prediction.git
   cd Wine-Quality-Prediction
