# AI Resume Analyzer

## Live Demo

Check out the live demo: [Demo Link](https://ai-resume-analyzer.streamlit.app/)


## Overview

AI Resume Analyzer is an LLM-powered Applicant Tracking System (ATS) simulator built using Google Gemini (Gemini Pro Vision), Python, and Streamlit. that evaluates resumes against job descriptions. The system performs semantic and keyword-level analysis to generate:Resume–JD match score, Missing keyword insights, Context-aware improvement suggestions.

This enables users to iteratively optimize resumes and improve ATS pass rates, also for Recruiters(HR) to find the right candidate.

## Features

- **Resume Analysis:**
  - Upload resume (PDF) and job description
  - AI evaluates:
    - Skills alignment
    - Experience relevance
    - Role fit
  - Output
    - summary
    - strenghts and weaknesses,
    - (percentage match, missing keywords, final thoughts) against the job description(JD).

- **Intelligent Suggestions**
  - Skill additions
  - Keyword optimization
  - Experience reframing

## Screenshot
![304501091-3149e25a-764c-4dca-927e-94ca740a06eb (1)](https://github.com/CodewithAbhi7/Application-Tracking-System-ATS-/assets/112254825/c6186309-9a64-4eaa-81ee-0147484d2cf8)

## System Workflow:

1.**Input Layer:**
  - User uploads resume + job description

2.**Preprocessing:**
  - PDF → Image conversion (every page converted to image)
  - Encoded for multimodal LLM input

3.**LLM Processing:**
  - Gemini Pro Vision analyzes:
    - Text semantics
    - Visual structure
    - Keyword alignment
  
4.**Output Generation:**
  - Summary
  - Strength and Weakness
  - Match score
  - Missing keywords
  - Resume feedback

## Tech Stack

- LLM: Google Gemini (Gemini Pro Vision)
- Backend: Python
- Frontend/UI: Streamlit
- PDF Processing: pdf2image, PIL
- Environment Management: python-dotenv

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/CodewithAbhi7/Application-Tracking-System-ATS-.git
2. ```bash
   pip install -r requirements.txt
3. ```bash
   streamlit run app.py

## Future Improvements
- Multi resume parsing
- Vector search (FAISS) for semantic similarity
- Hybrid scoring (LLM + embeddings + keyword engine)
