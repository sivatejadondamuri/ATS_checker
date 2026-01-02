# ATS Pro | AI-Powered Resume Optimizer

ATS Pro is a modern, single-page web application designed to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). Using the power of Google Gemini AI, the tool analyzes the semantic alignment between a user's resume and a target job description, providing a match score and actionable feedback.

## 🚀 Features

PDF Parsing: Automatically extracts text from uploaded PDF resumes.

AI Analysis: Direct comparison between Resume and Job Description using Google Gemini.

Visual Scoreboard: An animated, high-impact score gauge representing your match quality.

Three-Pillar Feedback:

Key Strengths: Highlights matching skills and experience.

Critical Gaps: Identifies missing keywords and requirements.

Action Plan: Provides 3-5 specific steps to improve the resume.

Single-Page Interface: A fast, responsive UI that fits entirely within the viewport.

Modern UI/UX: Built with Tailwind CSS and Plus Jakarta Sans for a premium feel.

## 🛠️ Tech Stack

Frontend: HTML5, JavaScript, Tailwind CSS, Lucide Icons.

Backend: Python, Flask.

AI: Google Generative AI (Gemini 2.5 Flash).

Extraction: PyPDF2.

## 📥 Installation & Setup

Clone the repository:

git clone https://github.com/sivatejadondamuri/ATS_checker.git  
cd ats-pro-checker

Install dependencies:

pip install flask requests PyPDF2 google-generativeai

Configure API Key:

Obtain a Google AI API Key from the Google AI Studio.

Open app.py and set the API_KEY variable or set it as an environment variable.

Run the application:

python app.py

The app will be available at http://localhost:8080.

## 🖥️ Usage

Upload: Drag and drop your resume in PDF format.

JD: Paste the text of the job description you are targeting.

Analyze: Click "Analyze Resume Now" and wait for the AI to process.

Improve: Review the "Critical Gaps" and "Action Plan" to tailor your resume for better results.

## 🤖 How it Works

The backend uses a specific System Instruction to turn Gemini into a critical ATS algorithm used by Fortune 500 companies. It doesn't just look for keyword matching; it performs a semantic analysis to see if the context of your experience actually meets the requirements of the job description.

## 📄 License

This project is open-source and available under the MIT License.
