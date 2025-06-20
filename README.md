📄 README.md Content
# 🧠 MindEase – Multilingual Mental Health Chatbot

MindEase is an AI-powered, multilingual mental health support chatbot that provides emotional assistance and intelligent conversation in multiple languages. It breaks language barriers and helps users feel heard, understood, and supported — anytime, anywhere.

---

## 🌐 Features

- 💬 Conversational chatbot using OpenAI's GPT
- 🌍 Multilingual translation using Google Translate API
- 🔐 Secure user authentication (Signup/Login)
- 💾 Saves conversation history per user
- 🌓 Light/Dark mode toggle
- 🎨 Beautiful pastel-themed responsive UI with animations
- 🔄 Real-time interaction via Flask backend and React frontend

---

## 🛠️ Tech Stack

- **Frontend:** React.js + TailwindCSS
- **Backend:** Flask (Python)
- **Database:** MongoDB
- **Translation API:** `deep-translator` / `googletrans`
- **AI Support:** OpenAI GPT (via API key)

---

## 🚀 Setup Instructions

### 🔐 Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Node.js & npm](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- OpenAI API key (from https://platform.openai.com)
- Google Translate key (optional; fallback available)

---

### 🧪 Backend Setup

```bash
cd multilingual-chatbot
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
Create a .env file:

OPENAI_API_KEY=your_openai_key
Run backend:

python3 app.py
🎨 Frontend Setup
cd client
npm install
npm start
📂 Project Structure

multilingual-chatbot/
│
├── client/                   # React frontend
├── routes/                   # Flask routes (auth, chat)
├── models/                   # MongoDB models
├── utils/                    # Translation & token logic
├── app.py                    # Main backend app
├── .env                      # API keys (excluded from repo)
└── README.md                 # This file
✨ Demo (Optional)


🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License

MIT


---

### ✅ After saving:


