📊 Behavioral Analysis using Email Activity
Data Science & AI Induction Project
📌 Project Overview
This project explores how meaningful behavioral insights can be inferred from raw, unstructured data using Data Science and basic Machine Learning techniques.
By analyzing email activity timestamps, the project aims to understand daily routines, activity patterns, sleep/inactivity periods, and differences between weekdays and weekends.
The project follows a complete data science pipeline, starting from raw data preprocessing to visualization, feature engineering, model training, and evaluation.
🎯 Objectives
Understand the end-to-end workflow of a data science project
Extract temporal features from unstructured data
Analyze daily activity and inactivity (sleep) patterns
Visualize behavioral trends over time
Train and evaluate a simple machine learning model
Incorporate contextual factors such as weekends and holidays
📂 Dataset
Source: Enron Email Dataset
Data Type: Unstructured email text
Key Information Used:
Email timestamps (embedded inside message text)
User-specific email activity
Only timestamp-based features were used; email content was not analyzed.
🛠️ Technologies Used
Python
Pandas – data manipulation
NumPy – numerical operations
Matplotlib – visualization
Scikit-learn – model training & evaluation
🧪 Project Workflow
1️⃣ Data Preprocessing
Extracted timestamps from raw email text
Handled missing and inconsistent values
Converted timestamps into standardized datetime format (UTC)
Filtered data for individual user analysis
2️⃣ Feature Engineering
Derived daily behavioral features such as:
Activity start hour
Activity end hour
Total active hours
Longest inactivity period (sleep duration)
Weekend indicator
3️⃣ Activity & Sleep Analysis
Identified active and inactive hours per day
Inferred sleep periods using longest inactivity logic
Compared routines across days
4️⃣ Visualization
Daily activity heatmaps
Trends in sleep duration and activity hours
Weekday vs weekend behavioral comparisons
5️⃣ Machine Learning
Built a Logistic Regression model
Used engineered behavioral features as inputs
Split data into training and testing sets
6️⃣ Model Evaluation
Accuracy
Precision, Recall, F1-score
Feature importance analysis
Interpretation of results and limitations
7️⃣ Contextual Analysis
Weekend vs weekday behavior comparison
Discussion of holidays and irregular days
Interpretation of anomalies in activity patterns
📈 Key Insights
Temporal patterns reveal consistent behavioral routines
Inactivity periods are strong indicators of sleep/rest
Weekends show delayed activity and longer inactivity
Behavioral features provide more insight than raw activity volume
⚠️ Limitations
Email activity is only a proxy for real behavior
Some days contain sparse or irregular data
Holidays were inferred indirectly
Model assumes linear separability
