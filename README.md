# 📊 Predicting Customer Conversion: Will they say Yes?

This project explores whether customer behavior can be used to predict subscription decisions in a marketing context. Inspired by real-world experience in fundraising and persuasion, the goal is to identify patterns behind the moment a customer decides to say “yes.”

## 🧠 Motivation
I’ve always been fascinated by the moment when someone decides to say “yes.” Through my experience at Northwestern Phonathon, I observed that successful outcomes were not random—there were clear patterns in how engagement and communication influenced decisions. This project extends that idea into a data-driven setting, using machine learning to model and understand those patterns.


## ⚙️ Methods
- Logistic Regression (baseline model)
- Lasso Regularization for feature selection
- Polynomial feature exploration (optional improvements)
- Threshold tuning for performance optimization

## 📈 Model Performance
- Accuracy: ~0.91  
- Precision: ~0.66  
- Recall: ~0.41 (baseline) → ~0.80 (after threshold tuning)  
- ROC AUC: ~0.94  

## 🔑 Key Insight
Traditional accuracy metrics can be misleading in imbalanced datasets. By lowering the classification threshold, the model significantly improves recall, allowing it to capture a larger proportion of potential customers.

## 💡 Business Implications
- Target high-probability customers to improve campaign efficiency  
- Increase engagement frequency to boost conversion likelihood  
- Use threshold tuning to balance outreach cost vs missed opportunities  
- Apply the model as a decision-support tool for marketing strategies  

## 🚀 Why This Project Stands Out
This project goes beyond standard classification by aligning model performance with real-world decision-making. Instead of optimizing for accuracy alone, it prioritizes recall to reflect the true cost of missing potential customers in a marketing setting.

## 📄 Files
- 📓 Notebook: `notebooks/customer_conversion_analysis_code.ipynb`  
- 📊 Report: `reports/customer_conversion_analysis_report.html`  

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, scikit-learn)
- Data preprocessing & feature engineering
- Statistical modeling & evaluation

---
