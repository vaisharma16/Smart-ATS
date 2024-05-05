# Smart ATS

## Summary

Smart ATS is an AI-powered Applicant Tracking System (ATS) designed to improve resumes by evaluating them against job descriptions. It utilizes Google's GenerativeAI library, specifically the Gemini Pro model, to provide detailed feedback on resumes.

## Features

- **Resume Evaluation**: Users can upload their resumes in PDF format.
- **Job Description Analysis**: Users input the job description against which their resume will be evaluated.
- **Matching Percentage**: Smart ATS calculates the percentage match between the resume and the job description.
- **Missing Keywords Detection**: The system identifies keywords and skills missing from the resume that are present in the job description.
- **Profile Summary Generation**: Smart ATS generates a profile summary highlighting the candidate's strengths and areas for improvement.

## Usage

1. Paste the job description into the provided text area.
2. Upload your resume in PDF format.
3. Click the "Submit" button to receive feedback.

## Requirements

- Python 3.x
- Streamlit
- PyPDF2
- dotenv
- google.generativeai

## Installation

To set up the project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/smart-ats.git

2. Clone this repository:

   ```bash
    pip install -r requirements.txt
   
3. Set up your environment variables by creating a .env file and adding your Google API key:

   ```bash
     GOOGLE_API_KEY=your_api_key_here
   
4. Run the Streamlit app:
   ```bash
   streamlit run app.py

