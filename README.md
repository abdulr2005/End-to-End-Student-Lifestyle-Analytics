# 🎓 Student Well-being Analytics — Machine Learning & Power BI

An end-to-end data science project that explores how lifestyle factors relate to student well-being and builds machine-learning models to identify students at higher risk of depression.

## 🎯 Project Goal
Analyze **100,000 student records** and turn lifestyle, academic, and demographic data into useful insights through a complete workflow: data exploration, preprocessing, predictive modeling, model comparison, and an interactive Power BI dashboard.

## 🧠 Machine Learning Workflow
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature preparation
- Class-imbalance handling
- Leakage-aware feature selection
- Logistic Regression, Random Forest, and XGBoost
- Hyperparameter tuning with GridSearchCV
- Evaluation with special attention to recall for the minority class

## 📊 Model Results

| Model | Accuracy | Recall — Depressed Class |
| --- | ---: | ---: |
| Logistic Regression | 65% | **66%** |
| Random Forest | 82% | 18% |
| XGBoost (Optimized) | **90%** | 58% |

Accuracy alone is not enough for an imbalanced classification problem, so recall for the depressed class is reported alongside it.

## 📈 Power BI Dashboard
The project also includes an interactive Power BI report for exploring:
- Depression rate
- Lifestyle patterns
- Sleep and well-being relationships
- Demographic and academic filters
- Stress-related insights

## 🛠️ Tech Stack
**Python · Pandas · NumPy · Scikit-learn · XGBoost · Jupyter Notebook · Power BI · DAX · Power Query**

## 📂 Repository Contents
- `student_lifestyle.ipynb` — complete ML workflow
- `student_lifestyle_100k.csv` — dataset used in the project
- `student_lifestyle(DB).pbix` — Power BI dashboard
- `student_lifestyle Screenshot .png` — dashboard preview

## 🚀 Run the Project
1. Clone the repository.
2. Open `student_lifestyle.ipynb` in Jupyter Notebook.
3. Run the notebook cells to reproduce the analysis and modeling workflow.
4. Open the `.pbix` file in Power BI Desktop to explore the dashboard.

---
**Portfolio focus:** End-to-end Data Science · Imbalanced Classification · Model Evaluation · Business Intelligence
