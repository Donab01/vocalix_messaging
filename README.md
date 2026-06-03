<div align="center">

# 🎙️ Vocalix
### An Inclusive AI Voice Messaging Platform

**Breaking communication barriers for speech-disabled and multilingual users through personalized voice cloning and real-time translation.**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)]()

[Features](#-features) • [Demo](#-demo)  • [Getting Started](#-getting-started) 

---

<!-- Add a demo GIF here once available -->
<!-- ![Vocalix Demo](assets/demo.gif) -->

</div>

---

## 🌍 The Problem

Over **1.5 billion people worldwide** live with speech or language disabilities. Millions more face communication barriers due to language differences. Existing messaging apps offer no meaningful accessibility for users who:
- Cannot produce natural speech due to disability
- Communicate in native languages that lack digital support
- Need to send voice messages across language barriers

**Vocalix solves this** by combining AI voice cloning, multilingual NLP, and real-time translation into a single inclusive messaging platform.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗣️ **Personalized Voice Cloning** | Clone and preserve a user's unique voice identity using MOSS-TTS |
| 🌐 **Multilingual Translation** | Real-time text translation across 3 languages via Google Translate API |
| 🔤 **Native Transliteration** | Convert native language scripts to English phonetics for broader compatibility |
| ♿ **Accessibility First** | Designed specifically for speech-disabled users with alternative input methods |
| ⚡ **Low Latency** | Voice cloning response under 5-10 seconds end-to-end |
| 💬 **Real-Time Messaging** | Seamless voice message exchange between users |

---

## 🎬 Demo

> 📸 **Screenshots and demo coming soon.** Star this repo to get notified when the live demo is deployed.


📹 **Video Walkthrough:** (https://drive.google.com/file/d/1o4ZtUhL9jmNcsIVaJatLku4IgqX296z/view?usp=drivelink)

---



### How it works

1. **User inputs** text or audio in their native language
2. **Translation module** converts content to the target language using Google Translate API
3. **Transliteration module** converts native scripts to English phonetics where needed
4. **Voice cloning engine** synthesizes speech in the sender's cloned voice using MOSS-TTS
5. **Recipient receives** a natural-sounding voice message in their preferred language

---

## 🛠️ Tech Stack

### Backend
- **[FastAPI](https://fastapi.tiangolo.com)** — High-performance Python API framework
- **[MOSS-TTS](https://github.com/open-mmlab/Amphion)** — Open-source neural TTS for voice cloning
- **[Google Translate API](https://cloud.google.com/translate)** — Multilingual translation
- **Python 3.10+** — Core language

### Frontend
- **[React.js 18](https://react.dev)** — UI framework

### Infrastructure
- **Hugging Face Spaces** *(planned)* — Model hosting and deployment

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or higher
- Node.js 18 or higher
- A Google Cloud account with Translate API enabled

### 1. Clone the repository

```bash
git clone https://github.com/Donab01/vocalix.git
cd vocalix
```

### 2. Set up the backend

```bash
# Create and activate virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Add your Google Translate API key to .env
```

### 3. Set up the frontend

```bash
cd frontend
npm install
```

### 4. Run the application

```bash
# Terminal 1 — Start backend
uvicorn main:app --reload --port 8000

# Terminal 2 — Start frontend
cd frontend
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_TRANSLATE_API_KEY=your_api_key_here
TTS_MODEL_PATH=./models/moss-tts
```

---


## 🤝 Contributing

Contributions are welcome! This project is especially looking for help with:
- Adding support for more regional Indian languages
- Improving voice cloning accuracy
- UI/UX accessibility improvements

```bash
# Fork the repo, then:
git checkout -b feature/your-feature-name
git commit -m "Add: your feature description"
git push origin feature/your-feature-name
# Open a Pull Request
```


## 👩‍💻 Author

**Dona Babu**  
AI/ML Engineer · CS Student @ MITS, Kerala  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/dona--babu)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/Donab01)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white)](mailto:donababu02@gmail.com)

---

<div align="center">

**If Vocalix helped you or inspired you, please consider giving it a ⭐**  
*It helps others discover the project and motivates continued development.*

</div>
