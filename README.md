---
title: ICT Hub Chatbot
emoji: 💬
colorFrom: blue
colorTo: gray
sdk: gradio
sdk_version: "5.49.1"
app_file: app.py
pinned: false
---

# 💬 ICT Hub Chatbot

> A smart conversational assistant for ICT Hub — built with Python, Gradio, and Machine Learning.

<img width="1919" height="955" alt="Screenshot 2026-05-21 041644" src="https://github.com/user-attachments/assets/33415633-e7bc-4f85-88d2-3a74329e8554" />

---

## ✨ Features

- 🧠 **TF-IDF + Naive Bayes** intent classification
- 🔁 **Rule-based fallback** for unrecognized inputs
- 📱 **Clean, mobile-friendly** Gradio interface
- 🧹 **NLP preprocessing** with NLTK (stopwords + lemmatization)
- 📊 **Excel-powered dataset** — easy to update and extend

---

## 🚀 Live Demo

Try it on Hugging Face Spaces → [OmarElhadidi/icthub-chabot](https://huggingface.co/spaces/OmarElhadidi/icthub-chabot)

---

## 🧠 How It Works

1. Loads questions and responses from `icthub_dataset.xlsx`
2. Cleans and lemmatizes input text using NLTK
3. Vectorizes text with TF-IDF
4. Predicts the intent category using Naive Bayes
5. Returns a matched response and displays it in the chat

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `app.py` | Main chatbot application |
| `icthub_dataset.xlsx` | Dataset with questions & responses |
| `icthub_logo.png` | ICT Hub logo for the UI |
| `requirements.txt` | Python dependencies |

---

## 🛠️ Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Omar-Elhadidi/icthub-chatbot.git
cd icthub-chatbot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
python app.py
```

Then open your browser at `http://localhost:7860`

---

## 📦 Requirements

- Python 3.8+
- gradio
- pandas
- numpy
- nltk
- scikit-learn
- openpyxl

---

## 👨‍💻 Author

**Omar Elhadidi**  
[GitHub](https://github.com/Omar-Elhadidi) · [Hugging Face](https://huggingface.co/OmarElhadidi)
