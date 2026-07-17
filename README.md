# AI Resume Shortlister

An AI-powered Resume Screening System that automatically ranks resumes against a Job Description using Large Language Models.

## Features

- Parse Job Descriptions into structured JSON
- Parse PDF resumes
- Parse DOCX resumes
- Extract skills, education, experience, projects
- Match resumes against Job Description
- Generate overall compatibility score
- Rank candidates automatically

---

## Tech Stack

- Python
- Groq API (Llama 3.3 70B)
- Pydantic
- PyPDF
- python-docx
- dotenv

---

## Folder Structure

```
resume-shortlister
│
├── resumes
├── outputs
├── src
├── README.md
├── requirements.txt
└── .env.example
```

---

## Installation

Clone repository

```bash
git clone https://github.com/yourusername/resume-shortlister.git

cd resume-shortlister
```

Create virtual environment

```bash
python -m venv .venv
```

Activate

Windows

```bash
.venv\Scripts\activate
```

Linux

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env`

```
GROQ_API_KEY=your_api_key_here
```

---

## Run

```
python src/main.py
```

---

## Example Output

```
Processing: Resume1.pdf

Score: 91%

Matching Skills:
Python
AWS
SQL
Git

Missing Skills
Docker

Verdict

Strong Match
```

---

## Future Improvements

- Streamlit Web UI
- Drag & Drop Resume Upload
- OCR Support
- Multiple LLM Support
- CSV Export
- ATS Score Visualization
- Interview Question Generator

---

## License

MIT
