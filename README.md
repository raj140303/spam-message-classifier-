# 📩 SMS Spam Classifier

This project is a **Flask-based machine learning application** that classifies SMS messages as either **Spam** or **Not Spam** using Natural Language Processing (NLP) and a Naive Bayes model trained on the popular SMS Spam Collection Dataset.

---

## 🚀 Demo

🔗 Live Link (after deployment):  
[https://your-render-url.onrender.com](https://your-render-url.onrender.com)

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
├── app.py
├── spam_classifier.ipynb
├── vectorizer.pkl
├── model.pkl
├── templates/
│   └── index.html
├── static/
│   ├── styles.css
│   ├── Home_Page.png
│   ├── Spam.png
│   └── Not_Spam.png
├── requirements.txt
└── Procfile
