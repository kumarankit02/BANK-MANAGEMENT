# 🏦 BANK MANAGEMENT SYSTEM

A simple yet functional Bank Management System built in Python with both **Console** and **Web (Streamlit)** interfaces.

---

## ✨ Features

### Core Banking Operations
- **Create New Account** (with validation: age ≥ 18, 4-digit PIN)
- **Deposit Money** (max ₹10,000 per transaction)
- **Withdraw Money**
- **View Account Details**
- **Update Account Information** (Name, Email, PIN)
- **Delete Account**

### Account Features
- Auto-generated unique account numbers (e.g., `x2N@G46`)
- Persistent data storage using JSON
- PIN-based secure authentication

---

## 📁 Project Structure


BANK-MANAGEMENT/
├── app.py              # Streamlit Web Application
├── hello.py            # Core Banking Logic (Clean Class)
├── main.py             # Console-based Application
├── data.json           # Database (user accounts)
└── README.md



---

## 🚀 How to Run

### 1. Web Application (Recommended)

```bash
# Install dependencies
pip install streamlit

# Run the app
streamlit run app.py

2. Console Application
  python main.py

🛠️ Technologies Used

Python 3
Streamlit - For modern web UI
JSON - For data persistence
pathlib & random - Core utilities


