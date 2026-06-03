# ai-pdf-chat-pipeline

An AI-powered pipeline to chat with your PDFs, right in the browser.

## Files
- `pdf_chat.html` — Frontend UI, open directly in any browser
- `pipeline_with_backend.ipynb` — AI pipeline + backend logic, run in Jupyter

## Tech Stack
- HTML / CSS / JS
- Python 3.8+
- Jupyter Notebook
- AI / ML backend

## Quick Start

### HTML interface
```bash
python -m http.server 8000
# then open http://localhost:8000/pdf_chat.html
```

### Notebook
```bash
python -m venv .venv
.\.venv\Scripts\Activate     # Windows
source .venv/bin/activate    # macOS / Linux

pip install jupyter
pip install -r requirements.txt  # if available

jupyter notebook
```

## Notes
- Check notebook cells for API keys or credentials before sharing publicly
- If a backend is needed, look for `app.py` or a startup cell in the notebook
- `requirements.txt` can be auto-generated from the notebook on request

---

KLE Technological University — B.E. Final Year Project, 2027
