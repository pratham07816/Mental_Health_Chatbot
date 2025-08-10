# 🧠 Mental Health Therapist Chatbot

An **AI-powered conversational assistant** designed to provide mental health support, active listening, and wellness resources.  
This project combines **Natural Language Processing (NLP)**, **sentiment analysis**, and **context-aware conversation flow** to create an empathetic chatbot experience.

---

## 📌 Features

- **24/7 Mental Health Support** – Always available for users in need.
- **Sentiment & Tone Analysis** – Detects user mood and adapts responses accordingly.
- **Context-Aware Conversations** – Remembers recent messages for coherent replies.
- **Resource Suggestions** – Recommends relevant exercises, helplines, and self-care tips.
- **Crisis Detection** – Identifies urgent cases and provides helpline information.
- **Multi-Platform Support** – Can be integrated into web, mobile, or messaging apps.

---

## 🏗️ Architecture


flowchart TD
    A[User Input] --> B[Frontend UI]
    B --> C[API Gateway]
    C --> D[NLU Module - NLP Model]
    D --> E[Sentiment & Tone Analysis]
    E --> F[Response Generator]
    F --> G[Resource & Crisis Management Module]
    G --> H[Frontend UI]


## ⚙️ Tech Stack

Frontend:
 - React.js / HTML / CSS / JavaScript
 - Tailwind CSS for styling

Backend:
 - Node.js + Express.js
 - REST API endpoints for message handling

AI/NLP:
 - OpenAI GPT API (or alternative NLP models)
 - Sentiment Analysis (VADER/TextBlob/Custom ML model)

Database:
 - MongoDB (storing conversation history & user data)

Other Tools:
 - Axios for API calls
 - dotenv for environment variables
 - Helmet & CORS for security

## 📌 Future Improvements
 - Voice-based conversation using Speech-to-Text & Text-to-Speech APIs.
 - Integration with wearables for stress/mood monitoring.
 - Support for multiple languages.
 - Offline mode with local NLP models.
 
## ⚠️ Disclaimer
This chatbot is not a substitute for professional medical advice or therapy.
If you are experiencing a crisis, please contact a certified mental health professional or helpline immediately.

## 📞 Mental Health Helplines 
 - India: AASRA - 91-9820466726
 - USA: 988 Suicide & Crisis Lifeline - Dial 988
 - UK: Samaritans - 116 123 (freephone)
