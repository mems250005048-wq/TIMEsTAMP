# 📊 Behavioral Analysis using Email Activity  
**Data Science & AI Induction Project**

---

## 📌 Project Overview

This project explores how meaningful behavioral insights can be inferred from raw, unstructured data using Data Science and basic Machine Learning techniques. By analyzing email activity timestamps, the project aims to understand daily routines, activity patterns, sleep/inactivity periods, and differences between weekdays and weekends.

The project follows a complete data science pipeline, starting from raw data preprocessing to visualization, feature engineering, model training, and evaluation.

---

## 🎯 Objectives

- Understand the end-to-end workflow of a data science project  
- Analyze activity and inactivity (sleep) patterns  
- Visualize behavioral trends over time  
- Train and evaluate a simple machine learning model  
- Incorporate contextual factors such as weekends and holidays  

---

## 📂 Dataset

- **Source:** Enron Email Dataset  
- **Data Type:** Unstructured email text  
- **Key Information Used:** Email timestamps embedded inside messages  
- **Note:** Only timestamp-based features were used; email content was not analyzed  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🧪 Project Workflow

### 1️⃣ Data Preprocessing
- Extracted timestamps from raw email text  
- Handled missing and inconsistent values  
- Converted timestamps into standardized datetime format (UTC)  
- Filtered data for individual user analysis  

### 2️⃣ Feature Engineering
- Activity start hour  
- Activity end hour  
- Total active hours  
- Longest inactivity period (sleep duration)  
- Weekend indicator  

### 3️⃣ Activity & Sleep Analysis
- Identified active and inactive hours  
- Inferred sleep using longest inactivity logic  
- Compared routines across days  

### 4️⃣ Visualization
- Daily activity heatmaps  
- Sleep duration trends  
- Weekday vs weekend comparisons  

### 5️⃣ Machine Learning
- Logistic Regression model  
- Behavioral features used as inputs  
- Train-test split  

### 6️⃣ Model Evaluation
- Accuracy  
- Precision, Recall, F1-score  
- Feature importance analysis  

---

## 📈 Key Insights

- Temporal patterns reflect consistent behavioral routines  
- Inactivity periods are strong indicators of sleep  
- Weekends show delayed activity and longer rest  
- Behavioral features are more informative than raw activity volume  

---

## ⚠️ Limitations

- Email activity is only a proxy for real behavior  
- Sparse data on some days  
- Holidays inferred indirectly  
- Linear model assumptions  

---

## 🔮 Future Work

- Use official holiday calendars  
- Extend analysis to multiple users  
- Apply clustering methods  
- Incorporate content-based features  

---

## 👤 Author

**Swarnika Thakur**  
Data Science & AI Induction Project
