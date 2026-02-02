# 🎓 Student Well-being Analytics: ML & BI Dashboard

## 📌 Project Overview
This project explores the relationship between student lifestyle factors (Study hours, Sleep, Social Media, etc.) and mental health. Using a dataset of **100,000 records**, I built a predictive system and an interactive dashboard to identify at-risk students.

## 🛠️ Tech Stack
- **Data Processing:** Python (Pandas, Numpy)
- **Machine Learning:** Scikit-learn, XGBoost
- **Optimization:** GridSearchCV for Hyperparameter Tuning
- **Business Intelligence:** Power BI (DAX, Power Query)

## 🚀 Key Technical Challenges & Solutions
- **Class Imbalance (92% vs 8%):** Applied `scale_pos_weight` in XGBoost and `class_weight='balanced'` in Logistic Regression to prioritize the minority class (Depression: True).
- **Data Leakage:** Identified and removed proxy variables (like Student_ID) to ensure model generalization.
- **Scale:** Optimized SVM and KNN to handle large-scale data efficiently.

## 📈 Dashboard Insights (Power BI)
The interactive dashboard provides:
- **Depression Rate %:** Calculated using custom DAX measures.
- **Lifestyle Impact:** Visualizing the correlation between <6 hours of sleep and mental health.
- **Demographic Filtering:** Slicers for Gender, Department, and Stress Levels.

## 📊 Model Performance
| Model | Accuracy | Recall (Depressed Class) |
| :--- | :---: | :---: |
| **Logistic Regression** | 65% | **66%** |
| **Random Forest** | 82% | 18% |
| **XGBoost (Optimized)** | 90% | 58% |

*Note: Logistic Regression and Optimized XGBoost provided the best balance for clinical screening.*

## 📂 How to Use
1. Clone the repo.
2. Open `Notebooks/student_lifestyle.ipynb` to see the ML workflow.
3. Open `Dashboard/Student_Insights.pbix` to view the Power BI report.
