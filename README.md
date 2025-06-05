# 📧 Email Spam Classifier

This project is a **machine learning-based email classifier** that detects whether an email is **spam or not spam (ham)** using Natural Language Processing (NLP) techniques.

It uses a trained model and vectorizer to process and predict based on user input. The project is built using Python and Flask for the backend web interface.

---

## 🔍 Features

- ✅ Classifies emails as **Spam** or **Not Spam**
- 🧠 Built using machine learning & NLP
- 📦 Pre-trained model and vectorizer (.pkl files)
- 🖥 Simple Flask web interface for interaction
- 🚀 Ready for deployment (includes Gunicorn support)

---

## 🧠 Tech Stack

| Component       | Tech Used            |
|-----------------|----------------------|
| Language        | Python               |
| ML Model        | Scikit-learn         |
| Web Framework   | Flask                |
| Deployment      | Gunicorn (Optional)  |
| Model Storage   | Pickle (.pkl files)  |

---

## 📁 Project Structure
<pre>
email-spam-classifier/
├── app.py # Flask app
├── main.py # ML logic / backend logic
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Python dependencies
└── .gitignore # Files ignored by Git
</pre>

yaml
Copy
Edit

---

## 🚀 How to Run Locally

1. **Clone the repository**
git clone https://github.com/your-username/email-spam-classifier.git
cd email-spam-classifier

cpp
Copy
Edit

2. **Create virtual environment (optional but recommended)**
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate

markdown
Copy
Edit

3. **Install dependencies**
pip install -r requirements.txt

markdown
Copy
Edit

4. **Run the application**
python app.py

yaml
Copy
Edit

The app will start locally at:  
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## ☁️ Deployment Tips

- Add `gunicorn` to `requirements.txt` (already added).
- Use Render, Railway, or Heroku for easy deployment.
- Set `web service` entry point to `app:app` if using Gunicorn.

---

## 📄 License

This project is licensed under the MIT License.
