# JanSaarthi 🚜🗣️  
**Multilingual Voice-Based AI Assistant for Government Welfare Schemes**

JanSaarthi is an open-source AI-powered assistant designed to bridge the gap between citizens and the numerous government welfare schemes available in India. By leveraging voice-based interfaces and local language support, it helps rural and underserved communities easily discover, understand, and access welfare schemes they are eligible for.

---

## 🌟 Key Features

- 🎙️ **Voice Input:** Accepts voice queries in regional languages via app, WhatsApp, or IVR.
- 🌐 **Multilingual Support:** Uses NLP and TTS tools to communicate in local Indian languages.
- 🔍 **Scheme Matching:** Finds relevant government schemes based on user profile (age, income, occupation, etc.).
- 📞 **Low-Tech Friendly:** Works on basic phones using voice calls for inclusive accessibility.
- ⚙️ **Open-Source & Scalable:** Built using modular open-source technologies for ease of expansion and customization.

---

## 🧠 Tech Stack

| Layer            | Technologies Used |
|------------------|-------------------|
| Speech-to-Text   | Whisper / Vosk |
| NLP & Translation| IndicTrans, Bhashini APIs |
| Chatbot Engine   | Rasa |
| Backend API      | FastAPI |
| Database         | PostgreSQL |
| Text-to-Speech   | Coqui TTS |
| Deployment       | Render / Railway / AWS / Localhost |

---

## 📂 Project Structure

```bash
JanSaarthi/
├── backend/
│   ├── app.py
│   └── api/
├── chatbot/
│   └── rasa_project/
├── models/
│   └── stt_tts/
├── data/
│   └── schemes_db.csv
├── docs/
│   └── architecture_diagram.png
├── README.md
└── requirements.txt
