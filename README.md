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

Welcome to the **ICT Hub Chatbot** — a rule-based conversational assistant built with **Python**, **Gradio**, and **Machine Learning**.  
It provides quick responses to ICT Hub–related queries using an Excel dataset.

<img width="1919" height="955" alt="Screenshot 2026-05-21 041644" src="https://github.com/user-attachments/assets/f8edb10f-46cb-4b01-a597-470553002eb3" />


---

## 🚀 Features
- TF-IDF + Naive Bayes–based intent classification  
- Rule-based fallback for unknown inputs  
- Clean, mobile-friendly Gradio UI  
- Preprocessing with NLTK (stopwords, lemmatization)  
- Supports your own Excel dataset

---

## 🧠 How It Works
1. Loads `icthub_dataset.xlsx`
2. Preprocesses and vectorizes text
3. Classifies the category using Naive Bayes
4. Returns a response from the same category
5. Shows chat history in Gradio

---

## 📂 Files
| File | Description |
|------|--------------|
| `app.py` | Main chatbot app |
| `icthub_dataset.xlsx` | Dataset with sample questions & responses |
| `icthub_logo.png` | Logo for chatbot UI |
| `requirements.txt` | Python dependencies |
| `README.md` | Project description and Hugging Face metadata |

---

## 🧩 Run Locally
```bash
pip install -r requirements.txt
python app.py
