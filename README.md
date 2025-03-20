# AI-Powered-Fake-Job-Posting-Detection

#📌 Project Overview
Fake job postings are a growing concern, often leading to scams and fraud. This project aims to classify LinkedIn job postings as real or fake using a Random Forest model. The model is trained on various features extracted from job descriptions to improve accuracy in identifying fraudulent listings.

📂 Dataset
The dataset consists of real and fake job postings with attributes like title, company name, location, job type, salary, and description.

Preprocessing includes text cleaning, feature engineering, and vectorization.

🛠️ Tech Stack
Programming Language: Python

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

Model: Random Forest Classifier

🔍 Approach
Data Preprocessing - Handled missing values, text vectorization (TF-IDF), and categorical encoding.

Exploratory Data Analysis (EDA) - Identified patterns and trends in fraudulent job postings.

Feature Engineering - Extracted relevant text-based and structured features.

Model Training & Evaluation - Trained Random Forest and fine-tuned hyperparameters for better accuracy.

Prediction & Insights - Classified job postings and provided insights into the distinguishing factors of fake listings.

📊 Results
✅ Achieved high accuracy in detecting fake job postings.
✅ Identified key fraudulent indicators such as vague job descriptions, unrealistic salaries, and generic email domains.
