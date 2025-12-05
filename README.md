# 📊 Credit Risk Prediction Model

This project builds a **machine learning model** to predict the credit risk of loan applicants using the **German Credit Dataset**.  
It includes data preprocessing, feature encoding, model training, evaluation, and a **Streamlit web application** to make real-time predictions.

---

## 🚀 Features

- 🔍 Exploratory Data Analysis (EDA)
- 🧹 Data cleaning and preprocessing
- 🎛️ Categorical feature encoding (LabelEncoder, TargetEncoder, etc.)
- 🌳 ML model training using **Extra Trees Classifier**
- 📈 Model evaluation and accuracy analysis
- 🖥️ Streamlit web app to predict creditworthiness
- 💾 Saved model and encoders (`.pkl` files)

---
## 📁 Project Structure
📦 credit-risk-model/
│
├── 📁 src/
│   ├── app.py                  # Streamlit application for predictions
│   └── utils.py                # Helper functions (optional)
│
├── 📁 models/
│   ├── extra_trees_credit_model.pkl    # Trained ML model
│   ├── 📁 encoders/                     # All feature encoders
│   │     ├── Sex_encoder.pkl
│   │     ├── Checking_account_encoder.pkl
│   │     ├── Saving_accounts_encoder.pkl
│   │     ├── Housing_encoder.pkl
│   │     └── target_encoder.pkl
│   └── ...
│
├── 📁 data/
│   └── german_credit_data.csv           # Dataset used for training
│
├── 📁 notebooks/
│   └── analysis_model.ipynb             # EDA + model development notebook
│
├── requirements.txt                     # Python dependencies
├── README.md                            # Project documentation
└── .gitignore                           # Files/folders to ignore in Git


---

## 🧠 Machine Learning Model

- **Algorithm:** Extra Trees Classifier  
- **Why?**  
  - Handles mixed types of features  
  - Robust to noise  
  - Works well with categorical encodings  
  - Fast and accurate  

---

## 🏃‍♂️ How to Run the Project

### **1️⃣ Install dependencies**
```bash
pip install -r requirements.txt
(If you don’t have a requirements file, generate one using:)
pip freeze > requirements.txt
#### **1️⃣ Run the Streamlit app**
streamlit run app.py
The app will open in your browser and allow you to input applicant details to get a predicted credit risk.
---
## 📊 Dataset Information
Source: German Credit Data

Samples: 1000

Task: Predict whether a person is a good or bad credit risk

Features:
* Age
* Job
* Housing
* Credit amount
* Duration
* Purpose
* Checking account status
And more…

📈 Model Evaluation
The model was evaluated using:
* Accuracy
* Confusion Matrix
* Feature Importance
* Train-test split validation

🛠️ Technologies Used
* Python
* Pandas, NumPy
* Scikit-learn
* Streamlit
* Matplotlib / Seaborn
* Jupyter Notebook

