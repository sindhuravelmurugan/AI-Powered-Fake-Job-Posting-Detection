# AI-Powered-Fake-Job-Posting-Detection

## 📌 Project Overview
Fake job postings have become a serious issue, leading to scams, financial fraud, and data theft. This project aims to **detect fraudulent job postings** on platforms like LinkedIn using a **Random Forest classifier**.

By analyzing job descriptions, company details, and other textual features, we train a model to distinguish between **real and fake job postings** with high accuracy.

---

## 📂 Dataset
- The dataset contains job postings labeled as **real** or **fake**, with attributes like:  
  - **Job Title**  
  - **Company Name**  
  - **Location**  
  - **Job Type**  
  - **Salary**  
  - **Job Description**  
- Preprocessing involves **text cleaning, feature extraction, and vectorization (TF-IDF)**.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - `scikit-learn` – for machine learning  
  - `pandas` – for data manipulation  
  - `numpy` – for numerical operations  
  - `matplotlib` & `seaborn` – for data visualization  
- **Model:** Random Forest Classifier  

---

## 🔍 Approach

1. **Data Preprocessing** 🛠️  
   - Removed duplicates, missing values, and irrelevant data.  
   - Cleaned job descriptions (removed special characters, stopwords, etc.).  
   - Converted categorical data into numerical features.

2. **Exploratory Data Analysis (EDA)** 📊  
   - Analyzed patterns in fake vs. real job postings.  
   - Identified common fraud indicators like **vague descriptions** and **generic emails**.

3. **Feature Engineering** 🏗️  
   - Used **TF-IDF** for text vectorization.  
   - Extracted key features from job descriptions and company details.

4. **Model Training & Evaluation** 🤖  
   - Trained a **Random Forest Classifier** for classification.  
   - Fine-tuned hyperparameters to improve accuracy.  
   - Evaluated using **precision, recall, and F1-score**.

---

## 📊 Results
✅ Achieved **high accuracy** in classifying fake job postings.  
✅ Identified key fraud indicators, helping prevent job scams.  
✅ Demonstrated that **text-based patterns can reveal fraud** in job listings.

---

## 🚀 How to Run

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/fake-job-detection.git
cd fake-job-detection
