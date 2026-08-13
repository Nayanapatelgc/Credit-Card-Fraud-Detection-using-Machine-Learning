# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a Machine Learning project developed to identify whether a financial transaction is legitimate or fraudulent. The application uses transaction details provided by the user and predicts the transaction status using a trained Machine Learning model. A user-friendly web interface is built using Streamlit to make predictions in real time.

---

## 🎯 Objective

The primary objective of this project is to reduce financial fraud by accurately detecting suspicious transactions using Machine Learning techniques. The application enables users to enter transaction details and instantly receive a fraud prediction.

---

## 🚀 Features

- Interactive web application built with Streamlit.
- Predicts fraudulent and legitimate transactions in real time.
- Machine Learning pipeline for preprocessing and prediction.
- User-friendly interface with simple input fields.
- Fast and accurate prediction using a trained model.
- Easy deployment and reusable prediction pipeline.

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Joblib
- Jupyter Notebook

---

## 📂 Project Structure

```
Credit-Card-Fraud-Detection/
│── fraud_detection.py              # Streamlit application
│── analysis_madel.ipynb            # Data analysis and model training
│── fraud_detection_pipeline.pkl    # Saved ML pipeline
│── AIML Dataset.csv                # Dataset
│── requirements.txt
│── README.md
```

---

## 📊 Dataset

The dataset contains transaction information including:

- Transaction Type
- Transaction Amount
- Sender Old Balance
- Sender New Balance
- Receiver Old Balance
- Receiver New Balance

These features are used to classify transactions as:

- **0 → Legitimate Transaction**
- **1 → Fraudulent Transaction**

---

## ⚙️ Project Workflow

1. Load the transaction dataset.
2. Perform data preprocessing and cleaning.
3. Encode categorical features.
4. Split the dataset into training and testing sets.
5. Train the Machine Learning model.
6. Save the trained model using Joblib.
7. Develop a Streamlit application.
8. Predict transaction status based on user inputs.

---

## 🖥️ User Inputs

The application accepts the following inputs:

- Transaction Type
- Transaction Amount
- Sender Old Balance
- Sender New Balance
- Receiver Old Balance
- Receiver New Balance

---

## 📈 Prediction Output

The model predicts one of the following:

- ✅ 0 -> Legitimate Transaction
- ❌ 1 -> Fraudulent Transaction

---

## ▶️ Installation

### Clone the Repository

```bash
git clone https://github.com/Nayanapatelgc/Credit-Card-Fraud-Detection.git
```

### Navigate to Project Folder

```bash
cd Credit-Card-Fraud-Detection
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run fraud_detection.py
```

---

## 📸 Application Screenshots

Add screenshots of:

- Home Page
- Input Form
- Legitimate Transaction Prediction
- Fraudulent Transaction Prediction

---

## 🔮 Future Enhancements

- Improve model accuracy using advanced algorithms.
- Deploy the application on Streamlit Cloud.
- Add data visualization dashboard.
- Implement Explainable AI (SHAP/LIME).
- Integrate with real-time banking transaction systems.
- Support batch transaction prediction.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Machine Learning model development
- Data preprocessing
- Feature engineering
- Model serialization using Joblib
- Building web applications with Streamlit
- Real-time prediction systems
- Python programming
- End-to-end ML project deployment

---

## 👩‍💻 Author

**Nayana Patel G C**

Computer Science Engineering Student

Python Full Stack Developer | Machine Learning Enthusiast | Data Analytics Learner

GitHub: https://github.com/Nayanapatelgc



---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.