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
2. **Set Up Environment**
It's recommended to use a virtual environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

3. **Install Requirements
**
pip install -r requirements.txt

🔗 4. **Download the Model File**
Download the pre-trained model file (ensemble.h5) from this link:

📥** Download ensemble.h5**

Place the file in the root directory of the project.

▶️ 5. **python app.py
**🧪 **Demo Features**
Image Upload + Classification

**Student mood detection:**

Bored

Confused

Engaged

Drowsy

Frustrated

Looking Away

Login and Signup system with OTP verification via email

📂** Project Structure**

├── app.py
├── requirements.txt
├── flowchart.txt
├── templates/
│   ├── home.html
│   ├── signup.html
│   ├── signin.html
│   ├── result.html
│   └── index.html
├── static/uploads/
├── ensemble.h5  ← download separately
├── .gitignore
└── README.md
📚 **Dataset Used**
Kaggle - Student Engagement Dataset

Dataset

🧑‍💻 **Developed by
**Shaik Mohammed Anays
📧 anasshaik630@gmail.com
🌐 Portfolio

🪪 ** License**
This project is licensed under the MIT License.

---

📌 Once you upload the `ensemble.h5` to Google Drive or Dropbox, send me the link and I’ll insert it above.

Let me know if you also want badges like:
- ✅ Python version
- ✅ Flask powered
- ✅ Made with ❤️ by Anays

I'd be happy to add them!



