# 🤖 AI-Based Resume Fraud Detector for HR Teams

## 📌 Problem Statement
In today's competitive job market, **up to 80% of resumes** contain some form of exaggeration, misleading information, or outright fraud. HR teams often spend countless hours manually verifying qualifications and experiences, leading to inefficiency and potential bad hires.

## 🛠️ Solution
This project is an **AI-powered system** that helps HR professionals **automatically detect fraud** in resumes. By **cross-verifying candidate details** like:
- Skills listed
- Past job roles
- LinkedIn profiles  
...the system flags inconsistencies and **predicts the likelihood of resume fraud**.

## 🔍 Key Features
- ✨ **NLP-based Resume Parsing**
- 🔗 **LinkedIn & Web Data Verification**
- 📊 **Fraud Score Prediction**
- 🔒 **Secure & Private Resume Handling**
- 🌐 **User-friendly Frontend for HR Teams**

## 🧠 How It Works
1. **Upload Resume** (PDF/Docx)
2. **AI parses content** (education, skills, experience)
3. **Cross-check with real-world data** (LinkedIn, job portals)
4. **Score each resume** based on consistency and credibility
5. **Flag potential red flags** for HR review

## 🔧 Tech Stack
| Layer | Tech |
|------|------|
| 🧠 AI/NLP | Python, spaCy, OpenAI GPT |
| 🗃 Database | MongoDB |
| 🌐 Frontend | Next.js, Tailwind CSS |
| 🔌 APIs | LinkedIn Scraper (if authorized), OpenAI, Resume Parser |
| ☁️ Hosting | Vercel / Render / Heroku |

## 🎯 Challenges Solved
- Handling **ambiguous job titles and skills**
- Preventing **false positives** (legitimate candidates wrongly flagged)
- Supporting **varied resume formats and templates**
- Respecting **data privacy and security** of sensitive resumes

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/resume-fraud-detector.git
cd resume-fraud-detector

# Backend Setup
cd backend
pip install -r requirements.txt
python app.py

# Frontend Setup
cd ../frontend
npm install
npm run dev
