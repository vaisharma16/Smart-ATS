Smart ATS
Smart ATS is an AI-powered Applicant Tracking System (ATS) designed to improve resumes by evaluating them against job descriptions. 
The system utilizes Google's GenerativeAI library, specifically the Gemini Pro model, to provide detailed feedback on resumes.

Features
Resume Evaluation: Users can upload their resumes in PDF format.
Job Description Analysis: Users input the job description against which their resume will be evaluated.
Matching Percentage: Smart ATS calculates the percentage match between the resume and the job description.
Missing Keywords Detection: The system identifies keywords and skills missing from the resume that are present in the job description.
Profile Summary Generation: Smart ATS generates a profile summary highlighting the candidate's strengths and areas for improvement.

Usage
Paste the job description into the provided text area.
Upload your resume in PDF format.
Click the "Submit" button to receive feedback.

Requirements
Python 3.x
Streamlit
PyPDF2
dotenv
google.generativeai

Installation
Clone this repository.
Install the required dependencies using pip install -r requirements.txt.
Set up your environment variables by creating a .env file and adding your Google API key.
Run the Streamlit app using streamlit run smart_ats.py.
