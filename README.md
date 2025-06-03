# 🛡️ Phishing Website Detector (PWD)

**Phishing Website Detector (PWD)** is a web application built with **Python Flask** that uses **Machine Learning** to detect whether a given website is **legitimate** or a **phishing** attempt. This project is designed to enhance cybersecurity awareness and prevent online frauds by helping users evaluate website URLs before visiting them.

![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![Flask](https://img.shields.io/badge/framework-Flask-orange)
![Security](https://img.shields.io/badge/security-focused-critical)

---

## 📌 Features

- 🔍 **URL Input Search Bar** – Enter a URL and check if it’s phishing or safe.
- 🤖 **Machine Learning Model** – Predicts based on multiple URL features.
- 📘 **About Page** – Learn about phishing and how to protect yourself.
- 💡 **Interactive UI** – Clean, intuitive, and responsive interface.
- 🧰 **Security-Focused** – Input sanitization, domain checks, and no external URL execution.

---

## 🧠 How It Works

1. User inputs a URL.
2. System extracts features (domain age, IP presence, search engine indexing, etc.).
3. ML model predicts if the site is **legit** or **phishing**.
4. Result is displayed instantly on screen with appropriate messages.

---

## 🔒 Security Measures

- Input validation & sanitization
- WHOIS-based domain information checking
- Google Index lookup
- Never opens or interacts with the actual URL
- Suitable for deployment with HTTPS using **Gunicorn**

---

## 🛠 Installation & Setup

### ✅ Prerequisites

- Python 3.9+
- `pip` package manager
- Git (optional)

### 📦 Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mostofaahmed101/phishing_website_detector_PWD.git
   cd phishing_website_detector_PWD
   ```
2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```
3. **Run the app locally:**

    ```bash
    python app.py
    ```
4. **Run the app locally:**

    ```bash
    http://127.0.0.1:5000/
    ```

---

## 📖 About Phishing
**Phishing** is a cyber attack that tries to trick you into giving up sensitive information by pretending to be a trustworthy source (like a bank or social media site). Stay informed and always verify links!
Learn more about phishing: <br>
    https://www.phishing.org/what-is-phishing <br>
    https://www.consumer.ftc.gov/articles/how-recognize-and-avoid-phishing-scams <br>
    https://en.wikipedia.org/wiki/Phishing

---

## 🎉 Acknowledgments
1. Flask & Python Community
2. Cybersecurity Awareness Initiatives
3. Dataset providers for phishing URLs


## 💬 Feedback & Support
Follow me for more information, take a look at my other projects <br>
**Website:** https://sites.google.com/view/mostofaahmed-official <br>
**Github:** https://github.com/mostofaahmed101
