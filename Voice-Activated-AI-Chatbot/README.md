# 🎙️ Voice-Activated AI Chatbot (Google Colab Version)

This is a simple yet powerful **voice-activated AI chatbot** built using Python. It's designed to respond to a wide range of commands such as searching Wikipedia, opening websites, telling the time, and simulating system commands — all adapted for execution on **Google Colab**.

---

## 🚀 Features

- ✅ Text-to-Speech using `gTTS`
- ✅ Wikipedia summaries with `wikipedia-api`
- ✅ Open websites via `webbrowser`
- ✅ Simulated voice input using `input()` (due to Colab limitations)
- ✅ Time-based greeting
- ✅ Custom responses (like "hello", "who are you", etc.)
- ❌ System commands (like shutdown/restart) are simulated only
- 🟡 Extendable for note-taking, reminders, etc.

---

## 🛠️ Technologies Used

- Python 3.8+
- Google Colab (cloud-based Jupyter Notebook)
- `gTTS` – Google Text-to-Speech
- `wikipedia-api`
- `webbrowser`
- Built-in libraries: `datetime`, `IPython.display`, `input()`

---

## 📌 How to Run

1. Open the `.ipynb` notebook in **Google Colab**.
2. Run the first cell to install required packages:
   ```python
   !pip install SpeechRecognition gTTS wikipedia-api
