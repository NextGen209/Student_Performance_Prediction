# 🎓 Student Performance Prediction using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

### 📊 AI/ML Academic Project  
### Predicting Student Academic Performance using Machine Learning Algorithms

</div>

---

# 📌 Overview

This project aims to predict student academic performance using various Machine Learning classification algorithms. The system analyzes multiple demographic and educational factors to determine whether a student is likely to perform well academically.

The project follows a complete Machine Learning workflow including:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- Performance Comparison

The following Machine Learning models were implemented:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

# 🎯 Objectives

- Analyze student performance patterns
- Understand factors affecting academic success
- Build predictive Machine Learning models
- Compare model performances using evaluation metrics
- Identify the best-performing algorithm

---

# 📂 Dataset

Dataset used in this project:

🔗 https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

The dataset contains information related to:

| Feature | Description |
|---|---|
| Gender | Student gender |
| Race/Ethnicity | Student ethnic group |
| Parental Level of Education | Parents’ educational background |
| Lunch | Standard or free/reduced lunch |
| Test Preparation Course | Course completion status |
| Math Score | Mathematics score |
| Reading Score | Reading score |
| Writing Score | Writing score |

---

# 🧠 Machine Learning Models

## 🔹 Logistic Regression
A supervised classification algorithm used for binary prediction problems.

### Advantages
- Simple and interpretable
- Fast training process
- Good baseline model

---

## 🌲 Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees.

### Advantages
- High accuracy
- Handles complex patterns effectively
- Reduces overfitting

---

## ⚡ Support Vector Machine (SVM)
A powerful supervised learning algorithm for classification tasks.

### Advantages
- Effective in high-dimensional spaces
- Strong classification capability
- Works well after feature scaling

---

# 📊 Exploratory Data Analysis (EDA)

The project includes detailed EDA covering:

✅ Dataset Overview  
✅ Missing Value Analysis  
✅ Statistical Summary  
✅ Correlation Analysis  
✅ Outlier Detection  
✅ Histograms & Boxplots  
✅ Gender-wise Performance Comparison  
✅ Impact of Parental Education  

### Key Insights

- Female students generally performed better in reading and writing.
- Students who completed the test preparation course achieved higher scores.
- Reading and writing scores showed strong positive correlation.
- Higher parental education positively influenced student performance.

---

# ⚙️ Data Preprocessing

The preprocessing pipeline included:

- Handling categorical features
- One-Hot Encoding
- Feature Scaling using `StandardScaler`
- Train-Test Splitting
- Feature Selection
- Target Variable Creation

### 🎯 Target Variable

Students were classified into:

| Class | Meaning |
|---|---|
| 1 | Good Performance |
| 0 | Poor Performance |

based on average examination scores.

---

# 📈 Model Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

# 🏆 Results

| Model | Performance |
|---|---|
| Logistic Regression | Strong baseline performance |
| Random Forest | Best overall accuracy |
| SVM | Excellent classification after scaling |

### ✅ Best Performing Model:
# 🌟 Random Forest Classifier

Reason:
- Better handling of feature relationships
- Reduced overfitting
- Strong ensemble learning capability

---

# 📷 Visualizations Included

The project contains multiple visualizations including:

- Histograms
- Heatmaps
- Boxplots
- Bar Charts
- Correlation Matrix
- Confusion Matrices
- Feature Importance Graphs

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Analysis |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# 📁 Project Structure

```bash
Student-Performance-Prediction/
│
├── data/
│   └── StudentsPerformance.csv
│
├── notebooks/
│   └── student_performance_prediction.ipynb
│
├── reports/
│   └── project_report.pdf
├── README.md
└── LICENSE