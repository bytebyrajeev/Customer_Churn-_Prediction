# Customer Churn Prediction

## 🔎 About The Project  
This project implements a full machine-learning pipeline to predict customer churn from historical data. It uses multiple classification algorithms — **Logistic Regression, Random Forest, K-Nearest Neighbors, SVM, XGBoost,** and **Gradient Boosting** — to estimate churn risk. The pipeline includes data cleaning, exploratory data analysis (EDA), feature engineering, class-imbalance handling (SMOTE / class-weighting), model training & evaluation, and analysis of key factors driving churn.

## 📂 Repository Structure  
- `prediction.ipynb` — Jupyter Notebook containing the full workflow: data loading, EDA, preprocessing, modeling, evaluation, and result interpretation.  
- customer_data.csv dataset files — raw or cleaned customer data used for modeling.  
  

## 🛠️ Tools & Technologies Used  
- **Python**  
- **pandas**, **NumPy** — for data manipulation and preprocessing  
- **matplotlib**, **seaborn** — for data visualization and exploratory analysis  
- **scikit-learn**, **XGBoost** — for building and evaluating machine-learning models  
- **imbalanced-learn** (or similar) — for handling imbalanced datasets using SMOTE or class weighting  
- **Jupyter Notebook** — for interactive analysis and documentation  

## 📈 Workflow / Steps Covered  
1. Load and inspect dataset  
2. Clean and preprocess data (handle missing values / categorical variables / feature scaling)  
3. Perform Exploratory Data Analysis (visualizations, feature-target relationships, outlier detection)  
4. Feature engineering and encoding; handle class imbalance (SMOTE / class weighting)  
5. Split data into training and testing sets  
6. Train multiple classification models (Logistic Regression, Random Forest, KNN, SVM, XGBoost, Gradient Boosting)  
7. Evaluate models using metrics such as accuracy, precision, recall, F1-score, and confusion matrix  
8. Compare model performances and select the best model(s)  
9. Analyze and interpret feature importances or influential factors to understand churn drivers  
10. Document findings and business-relevant insights  

## ✅ What This Project Demonstrates  
- End-to-end ML workflow on real-world structured data (from raw data to actionable insight)  
- Proficiency in data preprocessing, EDA, feature engineering, and handling imbalanced data  
- Comparative evaluation of multiple ML algorithms for classification tasks  
- Ability to derive business-oriented insights (e.g. which customer attributes contribute most to churn risk)  
- Familiarity with core Python data science libraries and tools  

## 🚀 How To Run / Use This Project  
```bash
# Clone the repository
git clone https://github.com/bytebyrajeev/Customer_Churn_Prediction.git

# (Optional) Create and activate a virtual environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS / Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
