# AI-powered Resume and Job Matcher

🚀 A project that parses resumes and job descriptions, then matches them using NLP and embeddings.

### Features
- Upload a resume and extract skills
- Parse job descriptions
- Match candidates to job postings
- Built with **FastAPI + NLP + Docker**

### Running locally
```bash
cd backend
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python -m spacy download en_core_web_sm
uvicorn app:app --reload --host 0.0.0.0 --port 8000
