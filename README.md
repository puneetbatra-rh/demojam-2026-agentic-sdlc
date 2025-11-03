# demojam-2026-agentic-sdlc


.env from e.nv.example
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

streamlit run app.py --server.address=0.0.0.0 --server.port=8501 --server.enableCORS=false --server.enableXsrfProtection=false