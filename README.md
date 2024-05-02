# AI Resume Analyzer

## Live Demo

Check out the live demo: [Demo Link](https://ai-resume-analyzer.streamlit.app/)


## Overview

This is an AI Resume Analyzer tracking system developed using Gemini Pro, Python, and Streamlit. The system allows users to upload job descriptions along with their resumes. The app then provides insights into the resume, including the percentage match with the job description and suggestions for improving the match.

## Features

- **Resume Analysis:**
  - Users can upload their resumes and job descriptions.
  - The system analyzes the resume and provides a summary, strenghts and weaknesses, percentage match with the job description.
  - Suggestions are given on how users can improve the match to increase their chances of selection.

## Screenshot
![304501091-3149e25a-764c-4dca-927e-94ca740a06eb (1)](https://github.com/CodewithAbhi7/Application-Tracking-System-ATS-/assets/112254825/c6186309-9a64-4eaa-81ee-0147484d2cf8)



## Use Case


### Streamlined Resume Optimization:

1.**User Submission:**
  - Users log in and securely upload their resume and the job description.
  - The system ensures confidentiality and data security throughout the process.

2.**Resume Analysis:**
  - Gemini Pro conducts a comprehensive analysis of both documents, considering key factors such as skills, experiences, and keywords.
  - Advanced algorithms ensure accurate assessment and provide a detailed match percentage.

3.**Provides Suggestions:**
  - Recommendations are tailored to the specific job description, highlighting areas for improvement in the resume.
  - Suggestions may include adding relevant skills, emphasizing specific experiences, or incorporating targeted keywords.

4.**User Action:**
  - Users update their resume based on the suggestions.
  - Re-upload the modified resume to see the impact on the match percentage.

5.**Impact Evaluation:**
  - After users update their resumes, the system recalculates the match percentage to quantify the impact of the changes.
  - The system provides ongoing feedback on how well their resume aligns with job opportunities.  change


## Technologies Used

- [Gemini Pro](https://gemini.com/) - This is an LLM model by Google which will perform task according to the prompt.
- [Python](https://www.python.org/) - Core programming language for backend development.
- [Streamlit](https://streamlit.io/) - Used for building interactive web applications with Python.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/CodewithAbhi7/Application-Tracking-System-ATS-.git
2. ```bash
   pip install -r requirements.txt
3. ```bash
   streamlit run app.py

