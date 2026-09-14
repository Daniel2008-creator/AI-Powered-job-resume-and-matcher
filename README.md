 AI-Powered Job Resume Matcher

 1. Project Description
Hiring teams spend hours manually scanning resumes to find candidates that fit a job description. This project solves that problem.

AI-Powered Job Resume Matcher automatically compares resumes against a job description and ranks candidates by how well they match. It uses NLP + embeddings to understand skills, experience, and keywords beyond simple keyword matching.

Goal: Save recruiters time and help job seekers see where their resume gaps are.

2. Features
- Resume Upload: Supports PDF and DOCX resume uploads
- Job Description Input: Paste JD or upload a file
- AI Matching Score: Ranks resumes from 0-100% match based on semantic similarity
- Skill Extraction: Pulls out key skills, experience, education from resumes
- Gap Analysis: Shows missing skills from the JD for each candidate
- Keyword Highlighting: Highlights matched keywords in the resume
- Export Results: Download ranked candidates as CSV

 3. Tech Stack
- Language: Python 3.10+
- AI/ML: OpenAI Embeddings / Sentence Transformers, spaCy, scikit-learn
- Backend: FastAPI / Flask
- Frontend: http://React.js + Tailwind CSS
- Database: PostgreSQL
- File Processing: PyPDF2, python-docx
- Deployment: Docker, Docker Compose
- Version Control: Git + GitHub

 4. How to run locally
 Backend
uvicorn app.main:app --reload[Recommended]

Frontend
cd frontend
npm install
npm start
App will run at: `http://localhost:3000`

5. Your Name + ContactName:
Adenisimi Daniel
Email: [adenisimidaniel525@gmail.com]
LinkedIn: [www.linkedin.com/in/
adenisimi-daniel-746554418
]
GitHub: [Daniel2008-creator]

