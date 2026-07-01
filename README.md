# resume_analyzer_ai
AI powered resume analyzer based on the given Designation and Job Description using Gemini model.
# 🤖 AI Resume Analyzer using Google Gemini AI

> An intelligent AI-powered Resume Analyzer that compares resumes with Job Descriptions (JD), calculates ATS scores, identifies strengths and weaknesses, performs SWOT analysis, and provides personalized career recommendations using Google's Gemini AI.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Live-red)
![Gemini](https://img.shields.io/badge/Google-Gemini_AI-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 🌐 Live Demo

🔗 https://resumeanalyzerai3.streamlit.app

---

# 📌 Overview

Hiring managers often receive hundreds of resumes for a single position. This project leverages **Google Gemini AI** to intelligently compare a candidate's resume with a given Job Description, providing a detailed ATS score and actionable insights to improve the candidate's chances of selection.

Unlike traditional keyword-based ATS tools, this application performs contextual analysis using Generative AI to evaluate resume quality, skill alignment, and overall job suitability.

---

# ✨ Key Features

### 📄 Resume Upload
- Upload Resume in PDF format

### 📝 Job Description Input
- Paste any Job Description

### 🤖 AI Resume Analysis
- Google Gemini AI powered evaluation

### 📊 ATS Score
- Generates ATS Compatibility Score

### ✅ Resume vs Job Description Comparison
- Skill Alignment
- Keyword Matching
- Experience Matching

### 💪 Strength Analysis
- Core Technical Skills
- Project Relevance
- Domain Knowledge

### ⚠️ Weakness Analysis
- Missing Skills
- Missing Keywords
- Domain Gaps

### 📈 Selection Prediction
- Probability of Selection

### 🎯 Skill Gap Identification
- Missing Technical Skills
- Recommended Improvements

### 📚 SWOT Analysis
- Strengths
- Weaknesses
- Opportunities
- Threats

### 💡 Personalized Recommendations
- Resume Improvements
- Career Suggestions
- Interview Preparation Tips

---

# 🏗️ System Architecture

```
                  Resume (PDF)
                       │
                       ▼
               Resume Text Extraction
                       │
                       ▼
            Job Description Input
                       │
                       ▼
              Google Gemini AI
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
 ATS Score      Resume Analysis   Skill Matching
        │              │              │
        └──────────────┼──────────────┘
                       ▼
          SWOT + Recommendations
                       │
                       ▼
             Detailed AI Report
```

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Backend Development |
| Streamlit | Interactive Web Application |
| Google Gemini AI | AI-powered Resume Analysis |
| PyPDF2 | Resume Text Extraction |
| Prompt Engineering | Intelligent AI Prompt Design |
| Markdown | AI Report Formatting |

---

# 📂 Project Structure

```
resume_analyzer_ai/

│── analysis.py
│── interface.py
│── pdf.py
│── requirements.txt
│── LICENSE
│── README.md
```

---

# ⚙️ Installation

Clone Repository

```bash
git clone https://github.com/Lokeswari3173/resume_analyzer_ai.git
```

Move into project

```bash
cd resume_analyzer_ai
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Application

```bash
streamlit run interface.py
```

---

# 📸 Application Screenshots

## 🏠 Home Page

<img width="1600" height="772" alt="image" src="https://github.com/user-attachments/assets/bfc073fa-dbd5-4302-bf9d-72549249ad4a" />

## 📄 Upload Resume & Enter Job Description

## 📊 ATS Score Generation

<img width="1600" height="772" alt="image" src="https://github.com/user-attachments/assets/49a8a21e-f916-4cb9-9811-2768a8ef5500" />
<img width="1600" height="768" alt="image" src="https://github.com/user-attachments/assets/287f43c5-e4dc-41f0-83d3-4c9323ea08e5" />

## ✅ Resume vs Job Description Comparison,💪 Strength Analysis, ⚠️ Weakness Analysis,📈 Probability of Selection,🎯 Skill Gap Analysis,📚 SWOT Analysis,💡 Personalized Recommendations,📋 Overall Candidate Assessment,🤖 Final AI Generated Report

<img width="1600" height="763" alt="image" src="https://github.com/user-attachments/assets/177c6665-907f-4ab5-b50f-b56e162e4c04" />
<img width="1600" height="766" alt="image" src="https://github.com/user-attachments/assets/1416b8f8-04b2-439b-90b4-72f761fc2289" />
<img width="1600" height="761" alt="image" src="https://github.com/user-attachments/assets/4fa1c826-b0f6-4a71-a156-d16ac50c076f" />
<img width="1600" height="766" alt="image" src="https://github.com/user-attachments/assets/7b5263a9-5a7b-4e97-8379-817920299d23" />
<img width="1600" height="759" alt="image" src="https://github.com/user-attachments/assets/022115b1-22fb-4247-b142-f640262a405e" />
<img width="1600" height="754" alt="image" src="https://github.com/user-attachments/assets/18b9ec92-2c65-4461-b194-4ff03087c415" />
<img width="1600" height="769" alt="image" src="https://github.com/user-attachments/assets/04722f78-c5dd-433a-b316-3807ea03c6e4" />
<img width="1600" height="760" alt="image" src="https://github.com/user-attachments/assets/eeac82eb-2297-4dcf-a4a1-b0876416d7a9" />
<img width="1600" height="762" alt="image" src="https://github.com/user-attachments/assets/563aff61-ecd7-40d8-b1dc-d20aec5c9ae0" />
<img width="1600" height="757" alt="image" src="https://github.com/user-attachments/assets/cdbbe450-ebab-45c5-964d-a8167fb00689" />
<img width="1600" height="762" alt="image" src="https://github.com/user-attachments/assets/bd8208fc-0b42-46e7-8280-b3bfeaf314bc" />
<img width="1600" height="758" alt="image" src="https://github.com/user-attachments/assets/ade94ae5-2802-43f4-82fa-091d5f227317" />


# 🔄 Workflow

```
Resume Upload
      │
      ▼
Extract Resume Text
      │
      ▼
Paste Job Description
      │
      ▼
Google Gemini AI Analysis
      │
      ▼
ATS Score Calculation
      │
      ▼
Resume vs JD Comparison
      │
      ▼
Strength Analysis
      │
      ▼
Weakness Analysis
      │
      ▼
Skill Gap Detection
      │
      ▼
SWOT Analysis
      │
      ▼
Recommendations
      │
      ▼
Final AI Report

# 🎯 Use Cases

- Students
- Freshers
- Experienced Professionals
- Career Coaches
- HR Professionals
- Recruiters
- Resume Optimization

---

# 🚀 Future Enhancements

- 📥 Download AI Report as PDF
- 📊 Interactive ATS Dashboard
- 📈 Skill Match Visualization
- 🌍 Multi-language Resume Analysis
- 📝 AI Cover Letter Generator
- 🎤 Interview Question Generator
- 📄 Resume Builder
- ☁️ Cloud Storage Integration

---

# 📚 Skills Demonstrated

✔ Python

✔ Streamlit

✔ Google Gemini API

✔ Prompt Engineering

✔ Natural Language Processing

✔ Resume Parsing

✔ Generative AI

✔ PDF Processing

✔ ATS Optimization

✔ LLM Applications

✔ AI Workflow Design

✔ UI Development

---

# 👩‍💻 Author

## Mangasamudram Lokeswari

**Data Science | Machine Learning | Generative AI**

GitHub

https://github.com/Lokeswari3173

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Show Your Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

🛠️ Contribute

📢 Share it with others

---
