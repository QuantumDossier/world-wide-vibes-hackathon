# Sovereign Engine: Agent-to-Agent-to-Human (A2A2H) Infrastructure
**World Wide Vibes Hackathon Submission**

## 📌 The Problem
"Shadow AI" is creating massive liability in the public sector. When city workers use generic, consumer-grade LLMs during critical infrastructure events, those models fail to cite local regulations (like the Alabama Competitive Bid Law), miss safety protocols (like OSHA/ADEM), and hallucinate unverified operational steps. 

## 💡 The Solution
The **Sovereign Engine** is an enterprise-grade middleware built for GovTech. It replaces Shadow AI with a secure A2A2H (Agent-to-Agent-to-Human) pipeline. 
1. **The System Agent** detects critical civic events (e.g., GIS/311 data).
2. **The Sovereign Backend Agent** (Gemini 3.1 Pro) cross-references live code and drafts strict, legally compliant operational payloads.
3. **The Human-Facing Agent** (Role-specific UI Gems) translates that complex JSON into distribution-ready tactical plans and public alerts for the end-user.

## 🛠️ The Tech Stack

* **Core Reasoning Engine:** Gemini 3.1 Pro (Hardened Adjudication & JSON Generation)
* **Prompt Orchestration:** Gemini Advanced / Thinking Model (System Architecture & Persona Design)
* **Dossier Generation:** Google Slides (Document Formatting)
* **Voiceover & TTS:** Google Vids (Educator Voice Profile)
* **Demo Assembly:** Clipchamp (Video Compilation & Transitions)

## 📂 Repository Contents
* `main.py`: The core FastAPI orchestration middleware showcasing the compliance loop and Persona constraints.
* `requirements.txt`: Environment dependencies.
* `Mayor_Digital_Twin_Payload.json`: The raw output demonstrating the 3.1 Pro model's deep reasoning and compliance tracing.
* `Sovereign_Executive_Persona.md`: The system instructions for the Mayor Reed backend agent.
* `Comm_Director_Persona.md`: The system instructions for the Miguel Diaz-Lucier front-end UI agent.

## 🚀 Quickstart
To run the Sovereign Engine API locally:
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Set your Google Cloud Project ID in `main.py`.
4. Run the server: `uvicorn main:app --reload`