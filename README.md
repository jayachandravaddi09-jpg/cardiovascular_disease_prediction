
<div align="center">

# ❤️ Cardiovascular Disease Prediction

### Machine Learning Based Heart Disease Detection System

<img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>

**Predicting cardiovascular disease using Machine Learning algorithms and patient health data.**

</div>

---

## 📌 Project Overview

Cardiovascular disease is one of the major health challenges worldwide.

This project develops a Machine Learning-based prediction system that analyzes patient health information and predicts the possibility of cardiovascular disease.

The project uses data preprocessing, exploratory data analysis (EDA), data visualization, feature engineering, and multiple machine learning classification algorithms to identify the best-performing model.

## 🎯 Objectives

- Analyze cardiovascular disease patient data.
- Perform data cleaning and preprocessing.
- Handle missing values and outliers.
- Perform Exploratory Data Analysis (EDA).
- Visualize relationships between features.
- Generate a correlation heatmap.
- Train and compare multiple ML algorithms.
- Identify the best-performing classification model.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |

## 📂 Dataset Information

**Dataset:** `cardi_train.csv`

- Total Records: 70,000
- Original Features: 11
- Target Variable: `cardio`

### Features

| Feature | Description |
|---|---|
| age | Patient age |
| gender | Patient gender |
| height | Height |
| weight | Weight |
| ap_hi | Systolic blood pressure |
| ap_lo | Diastolic blood pressure |
| cholesterol | Cholesterol level |
| gluc | Glucose level |
| smoke | Smoking status |
| alco | Alcohol intake |
| active | Physical activity |
| cardio | Disease target |

Target values:
- `0` – No Cardiovascular Disease
- `1` – Cardiovascular Disease

## ⚙️ Project Workflow

1. Data Collection
2. Data Loading
3. Data Preprocessing
4. Data Cleaning
5. Outlier Detection and Removal
6. Feature Engineering
7. Exploratory Data Analysis
8. Correlation Analysis
9. Train-Test Splitting
10. Feature Scaling
11. Model Training
12. Model Evaluation
13. Model Comparison
14. Final Model Selection

## 🧠 Machine Learning Algorithms

This project implements and compares five classification algorithms:

| Algorithm | Description |
|---|---|
| Logistic Regression | Linear classification |
| K-Nearest Neighbors (KNN) | Distance-based classification |
| Decision Tree | Tree-based classification |
| Random Forest | Ensemble learning |
| Support Vector Machine (SVM) | Kernel-based classification |

## 📊 Exploratory Data Analysis

The following visualizations are performed:

- Age distribution
- Gender distribution
- Cholesterol distribution
- Glucose distribution
- Smoking and alcohol analysis
- BMI distribution
- Blood pressure analysis
- Feature vs target analysis
- Correlation heatmap
- Pair plots

## ✨ Feature Engineering

Two additional features are created:

**1. BMI (Body Mass Index)**

BMI is calculated using height and weight.

Formula:

BMI = Weight (kg) / Height (m)²

**2. Pulse Pressure**

Pulse Pressure = Systolic BP - Diastolic BP

These features provide additional information for cardiovascular disease prediction.

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

The best-performing model is selected based on test accuracy.

> Note: Run the notebook to obtain the actual model accuracy values. No unverified accuracy figures are reported here.

## 🚀 Installation and Execution

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Navigate to the project**

```bash
cd Cardiovascular-Disease-Prediction
```

**Step 3: Install dependencies**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**Step 4: Start Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open the notebook:

`cardiovascular_disease_prediction.ipynb`

Make sure `cardi_train.csv` is available in the working directory.

## 📌 Project Outcomes

- Cleaned and processed patient health records.
- Performed detailed exploratory data analysis.
- Identified important cardiovascular risk indicators.
- Compared five machine learning algorithms.
- Selected the best-performing model based on evaluation results.

## 🔮 Future Enhancements

- Develop a web-based prediction application.
- Integrate Flask or FastAPI.
- Build an interactive patient dashboard.
- Deploy the ML model online.
- Add real-time cardiovascular risk prediction.

## 👨‍💻 Author

**Jayachandra Vaddi**

- AI/ML Engineer
- Python Developer
- Machine Learning Enthusiast
- Generative AI Enthusiast

### Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github)](https://github.com/jayachandravaddi09-jpg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/jaya-chandra-0440a32a7/)

---

<div align="center">

### ⭐ If you find this project useful, give it a star!

**Built with ❤️ using Python and Machine Learning**

</div>
