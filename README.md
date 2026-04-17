# 👩‍💻 Women Safety Prediction & Assistance System

## 📌 Project Overview
This project is a **Women Safety Web Application** developed using **Django, Python, and Machine Learning concepts**.  
It aims to enhance women's safety by providing features like crime prediction, emergency alerts, route assistance, and data visualization.

---

## 🎯 Objective
The main goal of this project is:
- To predict crime rates against women based on historical data
- To provide safety assistance features like emergency alerts
- To visualize crime data for awareness
- To help users find nearby police stations

---

## 🛠️ Technologies Used

### 💻 Backend:
- Python
- Django Framework

### 🗄️ Database:
- MySQL (via XAMPP) / SQLite (optional)

### 📊 Data & ML:
- Pandas
- NumPy
- Pickle (for model storage)

### 📈 Visualization:
- Matplotlib
- Seaborn

### 🌐 Frontend:
- HTML
- CSS

### 📡 Other:
- Google Maps (for routing)
- SMTP (Email alerts)

---

## 📂 Project Structure


women/
│
├── Dataset/ # Crime dataset
├── model/ # Trained ML model
├── Safety/ # Django main project
├── SafetyApp/ # Django app (views, logic)
├── templates/ # HTML files
├── static/ # CSS, images
├── db.sqlite3 # Database (if SQLite used)
├── manage.py # Django entry point
└── requirements.txt # Dependencies


---

## ⚙️ Features

### 🔐 1. User Authentication
- User Registration
- User Login

---

### 📍 2. Route Assistance
- Shows nearest police station using Google Maps

---

### 📊 3. Crime Prediction
- Predicts crime rate based on selected state

---

### 🔥 4. Heatmap Visualization
- Displays top crime states using heatmap

---

### 🧠 5. Machine Learning Model
- Uses trained model to show accuracy graph

---

### 🚨 6. Panic Button
- Sends emergency email to registered user

---

## 🚀 How to Run the Project

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Start XAMPP
Start Apache
Start MySQL
Step 4: Setup Database
Open: http://localhost/phpmyadmin
Create database: safety
Create table register with columns:
Field	Type
id	INT (Auto Increment)
username	VARCHAR(100)
password	VARCHAR(100)
mobile	VARCHAR(20)
email	VARCHAR(100)
address	VARCHAR(255)
Step 5: Run Server
python manage.py runserver
Step 6: Open Browser
http://127.0.0.1:8000/
📸 Screens (Features)
Home Page
Login / Signup
Dashboard
Crime Prediction
Heatmap
Route Map
Panic Alert
⚠️ Limitations
Uses basic ML model (not real-time)
Email feature uses static credentials
Not deployed online
Limited dataset
🔮 Future Enhancements
Real-time crime data integration
Mobile app version
GPS tracking
AI-based danger detection
Secure authentication system
👨‍🎓 Academic Use

This project is developed for:

Mini Project / Semester Project
Demonstration of ML + Web Integration
📢 Conclusion

This system provides a basic but effective solution for women safety by combining:

Machine Learning
Data Visualization
Web Development
🙌 Author

Raj Pandey
B.Tech CSE (Data Science)

⭐ Note

This project is for educational purposes only.


---

# ✅ What to do now

1. Create file in your project:
