# loan-predictor
# 🏦 Loan Approval Prediction App

A machine learning web application built with Streamlit that predicts 
whether a loan will be approved or rejected based on applicant details.

## 🚀 Live Demo
[Click here to view the app](https://your-app-link.streamlit.app)

## 📋 Features
- Secure login system
- Supports Home Loan, Car Loan, and Education Loan
- Real-time loan eligibility prediction
- Clean and interactive UI

## 🛠️ Tech Stack
- Python
- Streamlit
- Scikit-learn
- Pandas
- Pickle

## 📁 Project Structure
loan-predictor/
├── app.py                  # Main Streamlit app
├── model.pkl               # Trained ML model
├── scaler.pkl              # Feature scaler
├── requirements.txt        # Python dependencies
└── loan_approve_dataset.csv  # Dataset used for training

## ⚙️ How to Run Locally
1. Clone the repository
   git clone https://github.com/your-username/loan-predictor.git

2. Install dependencies
   pip install -r requirements.txt

3. Run the app
   streamlit run app.py

## 🔐 Login Credentials (Demo)
- Username: admin
- Password: 1234

## 📊 Input Features
| Feature | Description |
|---|---|
| Gender | Male / Female |
| Marital Status | Married / Not Married |
| Dependents | Number of dependents |
| Education | Graduate / Not Graduate |
| Self Employment | Yes / No |
| Annual Income | Applicant's yearly income |
| Loan Amount | Requested loan amount |
| Loan Duration | Loan repayment period |
| CIBIL Score | Credit score (0–1000) |
| Assets | Total assets value |

## 🤝 Contributing
Pull requests are welcome!

## 📄 License
This project is open source and available under the MIT License.
