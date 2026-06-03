# ai-pdf-chat-pipeline

An AI-powered pipeline to chat with your PDFs, right in the browser.

---

## Overview

This project combines a browser-based PDF chat interface with a
Jupyter notebook backend pipeline — built for exploring how AI can
make PDF content conversational and queryable without any server setup.

---

## Project Structure

pdf_chat.html            — Frontend UI for PDF interaction (open in browser)
pipeline_with_backend.ipynb  — Jupyter notebook with AI pipeline + backend logic

---

## Tech Stack

- HTML / CSS / JS  — frontend interface
- Python 3.8+      — notebook runtime
- Jupyter          — interactive pipeline environment
- AI/ML backend    — PDF processing and chat logic

---

## Getting Started

### 1. Open the HTML Interface

Option A — direct open:
  Double-click pdf_chat.html in your file explorer.

Option B — local server (recommended):
  python -m http.server 8000
  Then visit: http://localhost:8000/pdf_chat.html

### 2. Run the Notebook

# create virtual environment
python -m venv .venv
.\.venv\Scripts\Activate      # Windows PowerShell
source .venv/bin/activate     # macOS / Linux

# install dependencies
pip install jupyter
pip install -r requirements.txt  # if available

# launch
jupyter notebook

Open pipeline_with_backend.ipynb from the Jupyter interface.

---

## Notes

- Check notebook cells for API keys or credentials before sharing.
- If a backend server is required, look for app.py or a startup cell.
- A requirements.txt can be generated from the notebook on request.

---

KLE Technological University — B.E. Final Year Project
