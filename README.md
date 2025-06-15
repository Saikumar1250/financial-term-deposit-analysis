# 📊 Data-Driven Customer Targeting: Enhancing Term Deposit Campaign Success

This project performs exploratory data analysis (EDA), visualization, and predictive modeling on a financial marketing dataset to identify factors influencing customer subscription to term deposits.

---

## 📁 Files Included

- `Financial data.csv`: The dataset containing customer demographics, contact info, campaign data, and outcomes.
- `financial_data_analysis.py`: Python script for EDA, visualizations, and machine learning classification models.
- `README.md`: Project description and usage guide.

---

## 🔍 Key Insights

- Visualizations of age groups, job roles, and call durations.
- Subscription trends by day, month, marital status, and contact type.
- Logistic Regression and Random Forest models built to predict term deposit subscription.

---

## ⚙️ Tools Used

- **Python**: Data processing, modeling
- **Pandas, Seaborn, Matplotlib**: Data cleaning and visualization
- **Scikit-learn**: Model building and evaluation

---

## 📈 Model Performance

| Model               | Accuracy | MSE    |
|--------------------|----------|----------|
| Logistic Regression| ~0.9082     | ~0.092  |
| Random Forest       | ~0.9034    | ~0.096  |

---

## 🧠 Sample Prediction

The script includes a prediction example for a hypothetical customer profile using both models.

---

## ✅ How to Run

1. Make sure Python and the required libraries are installed (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
2. Run the script:
```bash
python financial_data_analysis.py
