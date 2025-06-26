# gemini-pro-streamlit-chatbot
This repository is about building a chatbot using Google's Gemini-Pro with streamlit.

This project is for educational and research purposes only.

---

## 🔧 Features

- 🌐 Real-time chat with Gemini-Pro (Google's LLM)
- 🧠 Memory-aware chat history within the session
- 📦 `.env` support to securely manage API keys
- 🚀 Streamlit-based responsive UI

---
## 🧱 Tech Stack

- [Streamlit](https://streamlit.io/)
- [Google Generative AI (Gemini-Pro)](https://ai.google.dev/)
- [Python-dotenv](https://pypi.org/project/python-dotenv/)

---

## 🔑 Setup Instructions

### 1. Clone this repository

```
git clone https://github.com/Ed-Gigaversity/Gemini-pro--ChatBot.git
cd gemini-pro-streamlit-chatbot
```
## 2. Create a virtual environment (optional but recommended)
```
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On macOS/Linux
```
## 3. Install dependencies
```
pip install -r requirements.txt
```
## 4. Set your Gemini API key
```
GOOGLE_API_KEY=your_gemini_api_key_here
```
🔐 You can get your API key from https://makersuite.google.com/app/apikey
## 5. Run the app
```
python -m streamlit run main.py
```
Your chatbot will open at http://localhost:8501
## 📁 File Structure
```
gemini-pro-streamlit-chatbot/
│
├── main.py              # Streamlit app entry point
├── requirements.txt     # Python dependencies
├── .env                 # Environment file (not committed to Git)
├── README.md            # Project documentation
└── LICENSE              # License info
```
## Acknowledgements
Google Generative AI
Streamlit
Python Dotenv