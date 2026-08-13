# Credit-Card-Fraud-Detection-using-Machine-Learning
A machine learning-based fraud detection system that identifies fraudulent financial transactions using scikit-learn and a class-weighted Logistic Regression model. Includes data preprocessing, feature engineering, model evaluation, and an interactive Streamlit web application for real-time fraud prediction.

🚀 Features
Detects fraudulent transactions using Machine Learning
Interactive web interface built with Streamlit
Real-time prediction based on user inputs
Data preprocessing integrated into the ML pipeline
Easy-to-use interface for testing transactions

🛠️ Technologies Used
Python
Streamlit
Scikit-learn
Pandas
NumPy
Joblib
Jupyter Notebook

📂 Project Structure
Credit-Card-Fraud-Detection/
│── fraud_detection.py              # Streamlit application
│── analysis_madel.ipynb            # Model training and analysis
│── fraud_detection_pipeline.pkl    # Trained ML model
│── AIML Dataset.csv                # Dataset
│── requirements.txt
│── README.md
📊 Dataset

The dataset contains transaction information such as:
Transaction Type
Transaction Amount
Sender Balance
Receiver Balance

These features are used to classify a transaction as:
0 → Legitimate Transaction
1 → Fraudulent Transaction

⚙️ Machine Learning Workflow
Load and preprocess the dataset.
Perform exploratory data analysis (EDA).
Encode categorical features.
Split the dataset into training and testing sets.
Train the Machine Learning model.
Save the trained model using Joblib.
Deploy the model with Streamlit.

▶️ Installation
Clone the repository:
https://github.com/Nayanapatelgc/Credit-Card-Fraud-Detection-using-Machine-Learning.git

cd Credit-Card-Fraud-Detection

Install dependencies:
pip install -r requirements.txt

Run the application:
streamlit run fraud_detection.py

💻 Application Interface
The user provides:
Transaction Type
Transaction Amount
Sender Old Balance
Sender New Balance
Receiver Old Balance
Receiver New Balance

The application predicts whether the transaction is:
✅ Legitimate Transaction
❌ Fraudulent Transaction

📈 Future Improvements
Improve model accuracy using ensemble learning.
Deploy the application on Streamlit Cloud.
Add transaction history and analytics dashboard.
Integrate explainable AI (SHAP/LIME) for prediction interpretation.
Connect with a real-time transaction database.



👩‍💻 Author
Nayana Patel G C
GitHub: https://github.com/Nayanapatelgc
