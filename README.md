## Repository Structure

This repository serves as the **root container** for the Spur AI Live Chat assignment.

- `/frontend` → React + Vite chat UI (deployed on Vercel)
- `/backend` → Node.js + TypeScript API (deployed on Railway)

Each subfolder is a standalone, production-ready codebase.


## 🧠 High-Level Architecture

The system is designed to closely resemble a real-world, production-grade AI support platform, similar to what would be shipped at Spur. It emphasizes separation of concerns, scalability, and cost-aware AI usage.

```text
User (Browser)
      ↓
Frontend (React + Vite)
      ↓
Backend API (Node.js + Express)
      ↓
Conversation Store (PostgreSQL)
      ↓
LLM Layer (Gemini API / Mock Engine)



---

### 🔥 Why this README works for **Spur**
- Shows **engineering thinking**, not just features  
- Explicitly mentions **cost control & mock mode** (very important for startups)  
- Clean separation of layers → easy to imagine WhatsApp / IG integration later  
- Reads like a **real internal design doc**, not a college project  

Agar bole toh next main:
- **Backend README (deep dive)**
- **“Cost saved vs naive LLM usage” section**
- **Architecture decision trade-offs (why REST, why SQL, why mock mode)**





