#CareerCraft: ATS-Optimized Resume Analyzer
Project Overview
CareerCraft helps users optimize resumes by analyzing content against job descriptions using Google's Gemini Pro model. It suggests missing keywords, skill improvements, and career guidance.

Project Flow
User Input: Users enter resume and job description details via the UI.
Backend Communication: Input is sent to the backend using a Google API key.
Model Processing: The Gemini Pro model processes the input.
Results Display: Processed results are formatted and shown to the user.
Setup
Install dependencies:
Copy code
pip install -r requirements.txt
Generate and initialize your Google API Key.
Run the app:
Copy code
python app.py
Key Features
Google API Integration
PDF Resume Handling
Gemini Pro Model Analysis
