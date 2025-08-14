# 🎓 Student Performance Prediction

An **end-to-end Machine Learning project** to predict student performance scores based on demographic and academic features.  
The project covers **full ML lifecycle** from problem understanding to cloud deployment using **Render**.

---

## 📌 Project Overview
This project predicts **student exam performance** (math, reading, and writing scores) using various features such as gender, ethnicity, parental education, lunch type, and test preparation course.  
It follows a modular structure with:
- Data ingestion
- Data transformation using pipelines
- Model training & hyperparameter tuning
- Prediction pipeline
- Deployment as a **Flask web application**

---

## 🚀 Project Workflow

1. **GitHub & Code Setup** – Repository structure creation and environment configuration.  
2. **Project Structure, Logging & Exception Handling** – Implemented clean architecture with logging and error tracking.  
3. **EDA & Model Training** – Exploratory Data Analysis to understand feature relationships; initial model building.  
4. **Data Ingestion** – Reading, validating, and preparing raw data.  
5. **Data Transformation Pipelines** – Feature scaling, encoding, and transformation.  
6. **Model Trainer** – Training multiple models with comparison metrics.  
7. **Hyperparameter Tuning** – Optimizing model performance.  
8. **Prediction Pipeline** – Building a reusable prediction pipeline.  
9. **Deployment** – Flask app deployed on **Render**.

---

## 🗂 Dataset
- **Source:** Kaggle – *Student Performance Dataset*  
- **File:** `stud.csv`  
- **Features:**
  - Gender
  - Race/Ethnicity
  - Parental Level of Education
  - Lunch type
  - Test preparation course
  - Reading Score
  - Writing Score
- **Target:** Predicted math score

---

## 🧹 Data Preprocessing
- Handled missing values
- Label encoding for categorical variables
- Standard scaling for numerical variables
- Pipeline-based preprocessing for consistency

---

## 🤖 Model Training
- Models tried: **Linear Regression, Random Forest, XGBoost, CatBoost**
- Selected model based on **R² Score, MAE, and RMSE**
- Hyperparameter tuning for best model performance

---

## 🌐 Deployment
The project is deployed on **Render**:
- **Live App:** [Click Here](https://student-performance-prediction-wykq.onrender.com/predictdata)

---

## 🛠 Tech Stack
- **Python**
- **Flask**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **CatBoost, XGBoost**
- **Render (Deployment)**

---

## 📬 Connect with Me
[Haathim Manaf – LinkedIn](https://www.linkedin.com/in/haathim-manaf)  
📧 Email: hathimmanafds@gmail.com

---

## 📜 License
This project is licensed under the MIT License.
