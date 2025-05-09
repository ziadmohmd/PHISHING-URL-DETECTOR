# 🔐 Phishing URL Detector

A Machine Learning-based web application that detects whether a given URL is **phishing** or **legitimate**, using trained models such as **Random Forest** and **LSTM**. It includes a modern, animated UI and optional Flask API backend for real-time predictions.

---

## 🚀 Features

- ✅ Detects phishing URLs based on structure and features
- 🔠 LSTM-based sequence analysis of raw URLs (optional)
- 🌐 Web interface built with HTML, Bootstrap 5, and JavaScript
- 🌗 Dark mode toggle and animated result display
- 🔁 Real-time prediction through Flask backend

---

## 🧠 Machine Learning Models

- **Random Forest**
- **Decision Tree**
- **Logistic Regression**
- **LSTM** (for sequence learning from raw URL characters)

---

## 📁 Project Structure

```
Phishing-URL-Detector/
├── static/
│   └── styles.css           # Optional custom styles
├── templates/
│   └── index.html           # Frontend HTML (Jinja2 templated)
├── phishing_model.pkl       # Trained ML model
├── app.py                   # Flask backend
├── requirements.txt         # Python dependencies
└── README.md                # You are here!
```

---

## ⚙️ Setup Instructions



### 2. 🧪 Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. 📦 Install Requirements

```bash
pip install -r requirements.txt
```

### 4. 🏃 Run the Flask App

```bash
python app.py
```

Then open `http://127.0.0.1:5000/` in your browser.

---

## 📊 Dataset Used

- **Source**: [Kaggle - Phishing Websites Dataset](https://www.kaggle.com/datasets)
- Features include:
  - URL length
  - Presence of HTTPS
  - WHOIS data
  - Symbol usage (`@`, `-`, `//`)
  - Domain age

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript
- **Backend**: Python, Flask
- **ML Libraries**: Scikit-learn, TensorFlow (for LSTM), Pandas, NumPy

---

---

## 💡 Future Work

- [ ] Add screenshot analysis using CNN
- [ ] Deploy to Heroku or Render
- [ ] Add browser extension integration
- [ ] Use live WHOIS/SSL verification

---

## 👨‍💻 Author

**MOHAMMED SIYAD**  
🧠 Machine Learning Enthusiast  
🔗 [GitHub](https://github.com/your-username) | 📧 [your-email@example.com]

---
