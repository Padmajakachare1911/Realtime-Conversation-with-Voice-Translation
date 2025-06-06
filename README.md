# Realtime-Conversation-with-Voice-Translation
This project is a real-time voice translator built using Machine Learning. It allows a conversation between an English-speaking user and a Spanish-speaking user. The model handles speech recognition, translation using a custom-trained Naive Bayes model, and text-to-speech for translated output.

✅ **Offline** — No APIs used  
✅ **Runs in Jupyter Notebook**  
✅ **Custom bilingual dataset and model**

---

## 🔧 Features

- 🎤 Speech recognition (English and Spanish)
- 🤖 Translation between English and Spanish
- 🔊 Text-to-speech output
- 🧠 Offline ML model with basic vocabulary

---

## 📁 Project Structure
voice_translator_project/
│
├── data/
│ └── bilingual_corpus.csv # Custom bilingual dataset
│
├── model/
│ ├── eng2span_model.pkl # English → Spanish model
│ ├── span2eng_model.pkl # Spanish → English model
│ ├── eng_vectorizer.pkl # Vectorizer for English
│ └── span_vectorizer.pkl # Vectorizer for Spanish
│
├── main.ipynb # Jupyter Notebook with full logic
└── README.md # This file




## 🔌 Requirements

Install dependencies:

```bash
pip install pandas scikit-learn SpeechRecognition gTTS pygame
