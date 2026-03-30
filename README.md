# 💼 Job Salary Prediction using Machine Learning

## 📌 Overview  
This project predicts job salaries using various machine learning models based on features like job title, experience, education level, skills count, company size, and location. The goal is to compare multiple regression models and identify the most effective one.

## ⚙️ Models Implemented  
- Multiple Linear Regression  
- Polynomial Regression  
- Support Vector Regression (SVR) *(trained on subset due to high computation)*  
- Decision Tree Regression  
- Random Forest Regression  

## 🛠️ Workflow  
- Data preprocessing and cleaning  
- Handling missing values  
- Encoding categorical variables (OneHotEncoder)  
- Feature scaling (StandardScaler for SVR)  
- Model training and evaluation  

## 📊 Model Performance (R² Score)

Multiple Linear Regression:  0.9534  
Polynomial Regression:       0.9716 ⭐  
Support Vector Regression:   0.9660  
Decision Tree Regression:    0.9358  
Random Forest Regression:    0.9620  

## 🏆 Best Model  
**Polynomial Regression** achieved the highest R² score of **0.9716**, making it the best-performing model for this dataset.

## 🚀 Key Insights  
- Polynomial Regression captured non-linear patterns effectively  
- SVR performed well but required sampling due to computational cost  
- Tree-based models provided solid performance with scalability  
- Proper preprocessing significantly improved model accuracy  

## 🛠️ Tech Stack  
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

## 💡 Future Improvements  
- Hyperparameter tuning (GridSearchCV)  
- Use of advanced models like XGBoost / LightGBM  
- Feature engineering for better generalization  

## 📁 How to Run  
1. Clone the repository  
2. Install required libraries  
3. Run the Python script or notebook  
