# 🧠 Predicting Human Personality using Machine Learning

This project focuses on building a machine learning model to predict human personality types based on user responses to various personal, behavioral, and psychological questions. The goal is to provide accurate and insightful predictions aligned with known personality classifications, such as the Big Five or MBTI framework.

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Project Pipeline](#project-pipeline)
- [Model Performance](#model-performance)
- [Results and Insights](#results-and-insights)
- [How to Run](#how-to-run)
- [Future Scope](#future-scope)
- [Contributors](#contributors)

## 📊 Project Overview

Personality prediction is increasingly used in hiring, education, therapy, and targeted marketing. In this project, we use machine learning algorithms to classify individuals into different personality types based on their answers to a set of questions.

## 📂 Dataset

- **Source**: [Kaggle / Custom Survey]
- **Shape**: 2000+ entries, 40+ features
- **Features**: User responses on traits like:
  - Openness
  - Conscientiousness
  - Extraversion
  - Agreeableness
  - Neuroticism
- **Target**: Predicted personality label (e.g., MBTI or Big Five category)

## 🎯 Objectives

- Clean and preprocess the data
- Explore feature relationships
- Train multiple classification models
- Evaluate models using appropriate metrics
- Predict personality types for new inputs

## 🛠️ Technologies Used

- **Language**: Python
- **Data Handling**: pandas, NumPy
- **Visualization**: matplotlib, seaborn
- **Modeling**: scikit-learn (Logistic Regression, SVM, Random Forest, KNN)
- **Metrics**: Accuracy, Confusion Matrix, Classification Report

## 🔁 Project Pipeline

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Data Cleaning & Preprocessing**
4. **Model Selection**
5. **Model Evaluation**
6. **(Optional) Model Deployment**

## 📈 Model Performance

| Model              | Accuracy    |
|--------------------|-------------|
| Logistic Regression| 93.58%      |
| Random Forest      | 93.83%      |
| SVM                | 93.83%      |
| Gradient Boosting  | 93.58%      |
|XGBoost             | 93.75%      |

## 🔍 Results and Insights

- The **Random Forest Classifier** performed best with the highest accuracy.
- Some personality traits (like openness and extraversion) had stronger correlations with predictions.
- Balanced dataset and proper encoding significantly improved model performance.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/personality-prediction.git
   cd personality-prediction
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Predicting\ Human\ Personality.ipynb
   ```

## 🔮 Future Scope

- Integrate deep learning (e.g., using LSTM on text responses)
- Deploy as a web app using **Streamlit** or **Flask**
- Use larger personality datasets with psychometric validation

## 👤 Contributors

- **Nihar Karia** – Data Analysis, Modeling, Documentation  
  [LinkedIn](https://www.linkedin.com/in/nihar-karia) | [GitHub](https://github.com/niharkaria)
