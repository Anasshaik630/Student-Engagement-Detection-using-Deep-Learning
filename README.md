# Student Engagement Detection using Deep Learning 🎓🤖

This is a Flask-based web application that detects **student engagement levels** from uploaded images using a trained **deep learning ensemble model**.

The goal is to help educators understand student moods (engaged, bored, confused, etc.) in online learning environments using image classification.

---

## 📌 Features

- 🧠 Predicts student engagement (e.g., Bored, Engaged, Drowsy, Frustrated, Confused, Looking Away)
- 🖼️ Upload image and classify instantly
- 🔐 User Signup, Login, and OTP verification via Email
- 📊 Frontend built with Flask, HTML templates, and SQLite DB for authentication
- 📦 Pretrained Ensemble Model using `Xception + NASNetMobile`

---

## 🖥️ Tech Stack

- **Frontend:** HTML, CSS, Flask templates
- **Backend:** Flask, Python
- **ML Frameworks:** Keras, TensorFlow
- **Database:** SQLite
- **Others:** Email OTP via smtplib, Image preprocessing, Deep learning model loading

---

## 🚀 How to Run the Project Locally

### 🔧 Prerequisites

- Python 3.10+
- Git
- `pip` for installing packages

### ⚙️ Setup

1. **Clone the repo**:

```bash
git clone https://github.com/Anasshaik630/Student-Engagement-Detection-using-Deep-Learning.git
cd Student-Engagement-Detection-using-Deep-Learning
