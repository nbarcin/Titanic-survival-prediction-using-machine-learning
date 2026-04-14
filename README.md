# 🚢 Titanic Survival Prediction (Machine Learning)

## 📌 Overview
This project focuses on predicting passenger survival on the Titanic using machine learning classification models.  

The Titanic dataset is one of the most well-known datasets in data science and is widely used to practice classification, data preprocessing, and feature engineering techniques.

---

## 📊 Dataset Information

The dataset contains **891 observations** and **12 features**, including:

- **PassengerId**
- **Survived** (Target Variable)
- **Pclass**
- **Name**
- **Sex**
- **Age**
- **SibSp, Parch**
- **Ticket**
- **Fare**
- **Cabin**
- **Embarked**

Some features contain missing values:
- **Age**
- **Cabin**
- **Embarked**

---

## ⚙️ Project Workflow

### 1️⃣ Data Analysis (EDA)
- Distribution analysis
- Survival comparison by gender, class, and age
- Correlation analysis
- Visualization with seaborn and matplotlib

### 2️⃣ Data Preprocessing
- Handling missing values:
  - Filled **Age** and **Fare**
  - Filled **Embarked** with mode
  - Dropped **Cabin** due to excessive missing values
- Encoding categorical variables
- Feature scaling (if needed)

### 3️⃣ Feature Engineering
- Created meaningful features
- Selected important variables based on correlation and domain knowledge

### 4️⃣ Model Training
Tested multiple classification models:
- Gradient Boosting
- Random Forest
- AdaBoost
- Logistic Regression
- Decision Tree
- KNN
- Naive Bayes

---

## 📈 Model Performance

| Model | Accuracy |
|------|---------|
| Gradient Boosting | **83.8%** |
| Random Forest | 82.1% |
| AdaBoost | 81.5% |
| Logistic Regression | 80.4% |
| Decision Tree | 78.7% |
| Naive Bayes | ~78% |
| KNN | 73.1% |

👉 **Best Model: Gradient Boosting Classifier**

---

## 📏 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

---

## 🔥 Key Insights

- Ensemble models outperform simpler models  
- Gender and passenger class strongly influence survival  
- Feature engineering significantly improves model performance  
- Proper handling of missing data is critical  

---

## 🚀 Results

- Achieved **~84% accuracy**
- Built a reliable classification model for survival prediction
- Identified key factors affecting survival probability

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
