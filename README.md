# AI War Simulator

A live web-based simulation that predicts and analyzes potential global conflicts between countries.

**Live Demo (Render):** [https://ai-war-simulator.onrender.com](https://ai-war-simulator.onrender.com)

## Features
- Select attacker and defender countries to simulate conflict.
- AI-generated risk prediction: High, Regional, or Limited.
- Shows direct & indirect effects, economic impact, and timeline.
- Displays affected allied countries.
- Generates a strategic report.
- Works on desktop & mobile.

---

## Tech Stack
- Python 3, Flask, Gunicorn
- HTML, CSS, JS
- Hosted on Render

---

## Run Locally
```bash
git clone https://github.com/GowthamiReddy87/ai_war_simulator.git
cd ai_war_simulator
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
pip install -r requirements.txt
python app.py
