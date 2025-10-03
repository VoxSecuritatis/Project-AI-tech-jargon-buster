# Tech Jargon Buster

### Repository page:  https://github.com/VoxSecuritatis/tech-jargon-buster

#### Streamlit demontration version:  https://tech-jargon-buster.streamlit.app

#### Development timeline (successes and failures):  https://github.com/VoxSecuritatis/AI-Project-tech-jargon-buster-dev-timeline/tree/main
---

**Executive Summary**

Tech Jargon Buster is a **Streamlit-powered application** designed to make IT and cybersecurity terminology accessible to everyone.  

By connecting to multiple **state-of-the-art Large Language Models (LLMs) via GitHub Models**, the app provides **side-by-side, plain-English explanations** of complex technical terms, enriched with real-world analogies.

This project showcases the integration of modern AI tools into an easy-to-use interface, supporting both **local development (Codespaces/desktop)** and **cloud deployment (Streamlit Community Cloud)**.  

It highlights practical AI application development, secure token handling, and multi-model orchestration in a single, user-friendly app.

---

## 🚀 Key Capabilities

- **Multi-model insights**: Parallel responses from **GPT-4.1**, **Mistral Small 3.1**, and **xAI Grok-3**.
- **Beginner-friendly outputs**: Explains jargon in plain English with relatable examples.
- **Creativity control**: Adjustable **temperature slider** balances precision vs. creativity.
- **Smart term detection**: Built-in IT keyword recognition, with manual override via `TERM:`.
- **Deployment ready**: Runs in GitHub Codespaces or can be deployed directly to **Streamlit Cloud**.

---

## 🌐 Business Value

- **Bridges the gap** between technical and non-technical stakeholders by simplifying jargon.
- **Educational tool** for onboarding, training, and democratizing IT/security concepts.
- **Portfolio demonstration** of modern AI application architecture and multi-model orchestration.
- Designed with **extensibility** in mind, enabling future integration of more models or features.

---

## 🛠️ Technical Overview

- Built in **Python (3.9+)** with **Streamlit** frontend.
- Uses **GitHub Models inference API** with a single **GitHub PAT** (`models:read` scope).
- Supported models:
  - `gpt-4.1`
  - `mistral-ai/mistral-small-2503`
  - `xai/grok-3`
- Secure configuration using `.env` (local) or `.streamlit/secrets.toml` (cloud).
- Modular design with separate connectors for each model.

---

## 📚 Attribution

- **Developed by**: Brock Frary  
- **Inspired by**: Jonathan Fernandes (LinkedIn Learning, *Creating AI Applications with Python and GitHub Models*)  
- **Purpose**: Personal learning, portfolio building, and demonstrating AI integration.  

---

## 📄 License

© 2025 Brock Frary. All rights reserved.  

---

