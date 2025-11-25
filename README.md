# Customer Churn Prediction & Salary Estimation

## 🚀 Live Demo
Check out the deployed Churn Predictiion and Salary Estimation app here:
**[👉 Click to View Streamlit App]([https://churn-classification-j5ngpuuhyadtbeja6vbhyi.streamlit.app/])** 
**[👉 Click to View Streamlit App]([https://churn-classification-u4gv27sdjcyv9h4ezfjjtn.streamlit.app/])**

## 📌 Project Overview
This repository contains two main machine learning applications:
1.  **Churn Classification:** A Deep Learning model (ANN) to predict if a customer will leave the bank/service.
2.  **Salary Estimation:** A Regression model to estimate salaries based on user inputs.

## 🧠 Models Used
### 1. Churn Prediction (ANN)
* **Architecture:** Artificial Neural Network (TensorFlow/Keras).
* **Input:** Customer demographics and account details.
* **Output:** Binary classification (Churn vs. Retained).

### 2. Salary Estimation
* **Type:** Regression Analysis.
* **Goal:** Predict continuous salary values based on experience/demographics.

---

## 💻 Execution Order & Installation
Follow these steps to set up the project locally.

### 1. Clone the Repository
Open your terminal and run:
```bash
git clone https://github.com/nuthanaabbojuu/Churn-Classification.git
cd [your-repo-name]
```

### 2. Create a Virtual Environment
It is recommended to use a virtual environment to manage dependencies and avoid conflicts.

```bash
# Windows
python -m venv venv

# Mac/Linux
python3 -m venv venv
```

### 3. Activate the Environment
Activate the virtual environment to ensure libraries are installed locally.

```bash
# Windows
.\venv\Scripts\activate

# Mac/Linux
source venv/bin/activate
```

### 4. Install Dependencies
Install all required Python libraries listed in the requirements file.

```bash
pip install -r requirements.txt
```

### 5. Run Churn Prediction App (ANN)
To launch the Churn Classification dashboard:

```bash
streamlit run app.py
```

### 6. Run Salary Estimation App
To launch the Salary Estimation dashboard:

```bash
streamlit run streamlit_regression.py
```
