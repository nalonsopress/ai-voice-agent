# ai-voice-agent
This project is a full-stack AI healthcare voice assistant.
It helps patients go from symptom input → doctor appointment → payment using voice and AI.
Built with:

Frontend: React
Backend: FastAPI (Python)
Database: PostgreSQL
AI: Gemini + GPT-4 + LangGraph




🔄 Core Workflow (End-to-End Flow)

User logs in
Speaks symptoms (via microphone + Web Speech API)
AI processes symptoms

Converts to structured medical terms
Suggests relevant specialists


System finds doctors

Matches specialists from the database
Shows available time slots


User books appointment
Payment is processed (Razorpay)

✅ In short:
Voice → AI analysis → Doctor match → Booking → Payment

🤖 Key Features

Voice interaction

Real-time speech-to-text
Natural language symptom collection


AI-powered analysis

Symptom normalization
Specialist recommendation


Doctor matching

Filters doctors by specialization
Retrieves availability


Appointment system

Scheduling + confirmation


Payment integration

Secure transactions via Razorpay




🏗️ Architecture

Frontend: React UI + voice interaction
Backend: FastAPI APIs + business logic
Database: PostgreSQL with stored procedures
AI services: Gemini, GPT-4, LangGraph
External tools: Web Speech API, Razorpay


📂 Project Structure

/backend → FastAPI services & AI agents
/frontend → React app
/sql → Database schema & stored procedures
Config files for environment variables and dependencies


🚀 Setup (High-Level)
To run locally:

Set up PostgreSQL database
Configure backend (.env with API keys + DB info)
Install backend dependencies and run FastAPI
Install frontend dependencies and run React app
(Optional) Configure Razorpay for payments


⚙️ Capabilities

Voice-based triage
AI-driven diagnosis support (not medical advice)
Automated doctor recommendation
Full appointment booking pipeline
Payment handling


🔮 Future Improvements

Multi-language support
Mobile app
Telemedicine (video calls)
Electronic health records integration
Real-time chat and analytics
