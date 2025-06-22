# 📩 SMS Spam Classifier

This project is a **Flask-based machine learning application** that classifies SMS messages as either **Spam** or **Not Spam** using Natural Language Processing (NLP) and a Naive Bayes model trained on the popular SMS Spam Collection Dataset.

---

## 🚀 Demo

🔗 Live Link (after deployment):  
https://spam-message-classifier-2.onrender.com
---

## 🧠 Features

- ✅ Preprocessing using NLTK (tokenization, stopword removal, stemming)
- ✅ TF-IDF vectorizer on top 3000 important tokens
- ✅ Trained using Multinomial Naive Bayes
- ✅ Achieved ~97% accuracy on test data
- ✅ Clean Bootstrap UI for easy message input
- ✅ Easy deployment via Render

---

## 📁 Project Structure

```bash
SMS_Spam_Classifier/
├── app.py                  # Flask web application
├── spam_classifier.ipynb   # Jupyter notebook (EDA + Model building)
├── vectorizer.pkl          # Saved TF-IDF vectorizer
├── model.pkl               # Trained Naive Bayes model
├── templates/
│   └── index.html          # Web page template (Flask Jinja)
├── static/
│   └── styles.css (opt)    # Optional custom styles
├── requirements.txt        # Required Python packages
└── Procfile                # Render deployment config
