# Resume Matcher — AI-Powered ATS Optimization Tool

AI-powered resume analysis platform that compares a resume against a job description and provides ATS optimization suggestions, semantic match scoring, resume rewrites, recruiter outreach templates, and interview preparation.

## Features

* Resume upload (PDF / DOCX)
* Job description parsing
* ATS match score calculation
* Skill gap analysis
* AI-powered resume rewriting
* Recruiter message generation
* Cold email generation
* Salary estimation
* Interview question generation

## Tech Stack

* Python
* Streamlit
* Google Gemini API
* PyPDF2
* python-docx
* ReportLab
* NLP / semantic similarity

## Architecture

Resume Input
→ Resume Parser
→ Job Description Parser
→ Matching Engine
→ AI Recommendation Layer
→ Streamlit UI

## Running Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Future Improvements

* Embedding-based semantic search
* Vector database integration
* Resume section scoring
* Job recommendation engine
* RAG pipeline for recruiter intelligence
