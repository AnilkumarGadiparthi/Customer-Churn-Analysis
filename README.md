# 📉 Customer Churn Analysis

This project is an end-to-end data analysis and machine learning solution to predict **customer churn**. It involves **data cleaning, exploratory data analysis (EDA)**, **feature engineering**, and building **predictive models** to help businesses understand why customers leave and how to retain them.

---

## 📌 Project Objectives

- Identify key factors that lead to customer churn
- Build machine learning models to predict churn
- Visualize and interpret insights through EDA
- Help businesses take preventive actions based on predictions

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── data/                 → Raw and processed datasets (CSV)
├── notebooks/            → Jupyter notebooks for EDA and modeling
├── models/               → Saved machine learning models (optional)
├── README.md             → Project documentation (this file)
└── requirements.txt      → Python dependencies
```

---

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
- **Jupyter Notebook** – Code development and reporting

---

## 🔍 Exploratory Data Analysis (EDA)

- Summary statistics and data types
- Null value analysis and treatment
- Visualizations: 
  - Histograms, boxplots, heatmaps
  - Churn vs. Non-Churn comparison
- Correlation analysis

---

## 🤖 Machine Learning Models

Trained multiple ML algorithms and compared performance:

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 78.3%    |
| Decision Tree       | 75.1%    |
| Random Forest       | **82.6%** ✅ Best |
| XGBoost             | 81.4%    |

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Key Insights

- High monthly charges and long customer service calls correlate with higher churn
- Customers without internet service tend to churn less
- Tenure (customer loyalty) has a strong inverse relation with churn

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AnilkumarGadiparthi/Customer-Churn-Analysis.git
   cd Customer-Churn-Analysis
   ```

2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Run the notebook to view the complete EDA and ML model pipeline.

---

## 🧑‍💻 Author

**Anil Kumar Gadiparthi**  
📧 ganachowdary07@gmail.com  
📍 Data Science & Machine Learning Enthusiast  

---

## ⭐ Feedback

If you like this project, feel free to give it a ⭐ on GitHub and share your thoughts!
