# 💳 Credit Card Approval System

An intelligent **Machine Learning-based Credit Card Approval System** that predicts whether a credit card application should be **Approved** or **Rejected** based on an applicant's financial and demographic information. The system automates the credit approval process, helping financial institutions make faster, more accurate, and data-driven decisions.

---

## 📖 Project Overview

Banks and financial institutions receive thousands of credit card applications every day. Manually reviewing each application is time-consuming and prone to human error. This project leverages Machine Learning to automate the approval process by analyzing applicant details and predicting approval eligibility.

The application compares multiple classification algorithms, selects the best-performing model, and integrates it into a Flask web application for real-time predictions.

---

## ✨ Features

- 🔐 User Registration and Login
- 📝 Credit Card Application Form
- 🤖 Machine Learning-Based Approval Prediction
- 📊 Data Visualization and Analysis
- 📈 Model Performance Comparison
- 💾 SQLite Database Integration
- 🌐 Responsive Flask Web Application
- 📜 Prediction History
- 👨‍💼 Admin Dashboard (Optional)
- ☁ IBM Watson Machine Learning Deployment Ready

---

## 🛠 Technologies Used

### Programming Language
- Python 3.11

### Machine Learning
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Joblib

### Backend
- Flask
- SQLAlchemy
- SQLite

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Data Visualization
- Matplotlib
- Seaborn

### Tools
- Git
- GitHub
- Jupyter Notebook
- IBM Watson Machine Learning

---

## 📂 Project Structure

```text
Credit-Card-Approval-System/
│
├── app.py
├── config.py
├── requirements.txt
├── README.md
├── dataset/
├── models/
│   └── best_model.pkl
├── notebooks/
├── templates/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── database/
├── routes/
├── utils/
├── deployment/
├── tests/
└── Dockerfile
```

---

## 🔄 Project Workflow

1. Download the Dataset
2. Import Required Libraries
3. Read the Dataset
4. Perform Exploratory Data Analysis (EDA)
5. Conduct Univariate & Multivariate Analysis
6. Data Cleaning and Preprocessing
7. Feature Engineering
8. Handle Missing Values
9. Encode Categorical Features
10. Train Machine Learning Models
11. Compare Model Performance
12. Save the Best Model
13. Build the Flask Web Application
14. Deploy the Model
15. Generate Real-Time Predictions

---

## 🧠 Machine Learning Models

The following classification algorithms are trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (Gradient Boosting)

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

The best-performing model is saved and used by the web application.

---

## 🗄 Database

SQLite is used to manage:

- User Information
- Credit Card Applications
- Prediction History
- Admin Data

---

## 💻 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Credit-Card-Approval-System.git
cd Credit-Card-Approval-System
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Login Page
- Registration Page
- Dashboard
- Credit Card Application Form
- Prediction Result
- Data Visualizations

---

## 🚀 Future Enhancements

- Explainable AI (XAI) Integration
- Fraud Detection Module
- Cloud Deployment
- REST API Support
- Email Notifications
- Mobile Application
- Role-Based Access Control

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is intended for educational and learning purposes. You may modify and extend it as needed.

---

## 👤 Author

**Dharani Pendem**

GitHub: https://github.com/your-username

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
