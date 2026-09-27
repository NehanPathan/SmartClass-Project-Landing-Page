# 🎓 SmartClass AI Attendance — Project Landing Page

A modern and responsive **Flask-based project landing page** created to showcase **SmartClass AI Attendance**, an AI-powered classroom attendance system.

The landing page presents the project's concept, key features, AI technologies, system workflow, screenshots, and overall user experience in a clean and professional format.

---

## 🌐 About SmartClass AI Attendance

**SmartClass AI Attendance** is an AI-based classroom attendance management system designed to automate the traditional attendance process.

The system combines **Face Recognition** and **Voice Recognition** to verify students and automatically record attendance.

It also includes features such as:

* 🎭 Face Recognition
* 🎙️ Voice Recognition
* 📋 Automatic Attendance
* 👨‍🎓 Student Management
* 🏫 Class Management
* 📱 QR-based Class Joining
* 📊 Attendance Records
* ☁️ Cloud Database
* 🔐 Authentication & Security

The original application uses Streamlit for its interactive interface and Supabase for cloud data management.

---

## ✨ Landing Page

This repository contains the **showcase website** for the SmartClass project.

The landing page is designed to visually communicate:

* Project overview
* Key features
* AI capabilities
* Face recognition workflow
* Voice recognition workflow
* Application screenshots
* Technology stack
* System architecture
* Project highlights
* Links to the main application

The goal is to provide visitors with a quick understanding of **what SmartClass is, how it works, and what technologies are used**.

---

## 🧠 AI Technologies

### Face Recognition

The SmartClass system uses facial recognition to identify and verify registered students during attendance.

Technologies include:

* `dlib`
* `face_recognition_models`
* `scikit-learn`

### Voice Recognition

Voice recognition is used to verify students through voice embeddings.

Technologies include:

* `librosa`
* `resemblyzer`

These components generate and process biometric features for student verification.

---

## 🛠️ Tech Stack

### Landing Page

* Python
* Flask
* HTML
* CSS
* JavaScript

### SmartClass Application

* Python
* Streamlit
* dlib
* face_recognition_models
* scikit-learn
* Librosa
* Resemblyzer
* NumPy
* Pandas
* Supabase
* bcrypt
* Segno
* Pillow

The underlying SmartClass application is Python-based and uses Streamlit, Supabase, biometric recognition libraries, and supporting data-processing tools.

---

## 📸 Project Showcase

The landing page includes visual sections showcasing the SmartClass application, including:

* Login / authentication
* Dashboard
* Student management
* Class management
* Attendance workflow
* Face recognition
* Voice verification
* Attendance records
* QR-based class joining

> Screenshots are included to demonstrate the application's interface and overall user experience.

---

## 🏗️ Architecture

At a high level, the SmartClass application follows this flow:

```text
                 ┌─────────────────────┐
                 │     Web Interface   │
                 │      SmartClass     │
                 └──────────┬──────────┘
                            │
              ┌─────────────┴─────────────┐
              │                           │
              ▼                           ▼
     ┌─────────────────┐        ┌─────────────────┐
     │ Face Recognition│        │ Voice Recognition│
     │                 │        │                 │
     │ dlib            │        │ Librosa         │
     │ Face Models     │        │ Resemblyzer     │
     │ Scikit-learn    │        │ Voice Embeddings│
     └────────┬────────┘        └────────┬────────┘
              │                           │
              └─────────────┬─────────────┘
                            ▼
                  ┌──────────────────┐
                  │    Attendance    │
                  │    Processing    │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │     Supabase     │
                  │     Database     │
                  └──────────────────┘
```

The architecture is based on the original SmartClass project structure.

---

## 🚀 Running the Landing Page Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/SmartClass-Project-Landing-Page.git
cd SmartClass-Project-Landing-Page
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask application

```bash
python app.py
```

The website should then be available at:

```text
http://127.0.0.1:5000
```

---

## 📁 Project Structure

```text
SmartClass-Project-Landing-Page/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── images/
│       ├── hero/
│       ├── screenshots/
│       └── features/
│
└── .gitignore
```

---

## 🎯 Purpose

This project is primarily a **visual showcase and presentation website** for SmartClass AI Attendance.

It separates the presentation layer from the main SmartClass application, making it easier to demonstrate the project to:

* Students
* Teachers
* Evaluators
* Hackathon judges
* Recruiters
* Project reviewers

---

## 🔗 Main Project

**SmartClass AI Attendance**

AI-powered classroom attendance using face and voice recognition.

The original project also provides a live Streamlit application.

---

## 👨‍💻 Author

**Nehan Khan Pathan**

Computer Science Engineer
AI • Full Stack Development • Software Engineering

---

## 📄 License

This project is intended for educational and demonstration purposes.
