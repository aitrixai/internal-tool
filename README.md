# Aitrix.ai Internal Dashboard

> A modern AI-powered desktop application for internal communication, onboarding, document/code collaboration, and productivity – built for Aitrix.ai’s internal teams.

---

## Features

- **Offline + Online Mode Toggle**
- **1:1 & Group Chat with AI Reply Suggestions**
- **Smart Onboarding (Email, Documents, Tutorials)**
- **Document Storage with OCR & Summarization**
- **GitHub/GitLab Code Viewer + AI Reviewer**
- **Meetings Calendar with Auto-Link & AI Notes**
- **AI Assistant for Daily Reports, Tasks, Docs**
- **Internal Wiki with Tutorials & SOPs**
- **Secure RBAC, Logs, File Access Tracking**

---

## Tech Stack

| Component       | Technology       |
|----------------|------------------|
| GUI            | PyQt6            |
| Backend        | Python, FastAPI  |
| Database       | SQLite / PostgreSQL |
| AI Services    | OpenAI, Whisper, Langchain |
| File Ops       | Tesseract OCR, SpeechRecognition |
| Version Control| Git, GitHub, Bitbucket |

---

## Getting Started

### Prerequisites

- Python 3.10+
- pip or poetry
- Windows 10+

### Installation

```bash
git clone https://github.com/aitrixai/internal-dashboard.git
cd internal-dashboard
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python main.py
