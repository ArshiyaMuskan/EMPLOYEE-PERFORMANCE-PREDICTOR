# 📊 Employee Performance Predictor

## 🚀 Project Overview

The **Employee Performance Predictor** is a Machine Learning-based application that predicts employee performance using key attributes such as experience, salary, training hours, and project completion data.

This project simulates a real-world HR analytics system and helps organizations make **data-driven decisions**.

---

## 🎯 Problem Statement

Organizations often struggle to evaluate employee performance objectively. This project aims to:

* Predict employee performance (Low, Medium, High)
* Assist HR in decision-making
* Improve workforce productivity using analytics

---

## 💼 Business Use Cases

* 📈 Identify high-performing employees
* ⚠️ Detect low performers early
* 🎓 Plan training and development
* 🏆 Support promotion decisions
* 🔁 Improve employee retention

---

## 🧠 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Model:** Random Forest Classifier
* **Frontend:** Streamlit

---

## 🏗️ Project Architecture

```
Data → Preprocessing → Model Training → Prediction → Streamlit UI
```

---

## 📁 Project Structure

```
Employee-Performance-Predictor/
│
├── app/
│   └── app.py                 # Streamlit application
│
├── src/
│   ├── 1_data_generation.py   # Synthetic dataset creation
│   ├── 2_preprocessing.py     # Data cleaning
│   ├── 3_eda.py               # Exploratory Data Analysis
│   ├── 4_model.py             # Model training & saving
│   └── 5_predict.py           # Prediction script
│
├── data/                      # Dataset files
├── models/                    # Saved model (.pkl)
├── outputs/                   # Graphs & results
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/employee-performance-predictor.git
cd employee-performance-predictor
```

### 2️⃣ Create virtual environment

```
python -m venv venv
```

Activate:

```
venv\Scripts\activate   (Windows)
source venv/bin/activate (Mac/Linux)
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Step 1: Generate Dataset

```
python src/1_data_generation.py
```

### Step 2: Preprocess Data

```
python src/2_preprocessing.py
```

### Step 3: Train Model

```
python src/4_model.py
```

### Step 4: Run Streamlit App

```
streamlit run app/app.py
```

---

## 📊 Output

* Performance Prediction (Low / Medium / High)
* Data Visualizations
* Feature Importance Analysis
* Employee Comparison Dashboard

---

## 🧪 Model Details

* Algorithm: Random Forest Classifier
* Evaluation Metrics:

  * Accuracy Score
  * Confusion MatrIX

---

## 🔮 Future Improvements

* 📂 CSV Upload for bulk predictions
* 📥 Downloadable reports
* 🌐 Deploy on Streamlit Cloud
* 🤖 Deep Learning integration
* 📊 Advanced dashboards

---

## 🧠 Key Learnings

* End-to-end ML pipeline development
* Data preprocessing and feature engineering
* Model training and evaluation
* Streamlit app development
* Debugging real-world issues

---

## 💬 Conclusion

This project demonstrates how Machine Learning can be applied to solve real-world HR problems by enabling data-driven employee performance evaluation.

---

## 👩‍💻 Author

ARSHIYA MUSKAN

---

## ⭐ If you like this project, give it a star!
