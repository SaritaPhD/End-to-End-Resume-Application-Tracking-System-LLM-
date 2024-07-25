# End-to-End-Resume-Application-Tracking-System-LLM

## ATS Resume Expert
## Overview
- ATS Resume Expert is a Streamlit-based web application that allows users to upload their resumes in PDF format and receive an analysis based on a provided job description. The application uses the Gemini Pro Vision model from Google's Generative AI to generate detailed feedback and evaluate the alignment of the resume with the job description.

## Features
- Job Description Input: Users can enter the job description in a text area.
- Resume Upload: Users can upload their resume in PDF format.
- Professional Evaluation: The application provides a detailed professional evaluation of the resume against the job description.
- Percentage Match: The application calculates the percentage match between the resume and the job description, highlighting missing keywords and providing final thoughts.

## Requirements
- Python 3.10+
- Streamlit
- dotenv
- base64
- PIL (Pillow)
- PyPDF2
- google-generativeai
### Dependencies: If pdf2image is used instaed of pyPDF2 then pdf2image requires poppler to be installed on your system. Make sure poppler is installed:

- On macOS: brew install poppler
- On Ubuntu: sudo apt-get install -y poppler-utils

## Installation
- Clone the repository: git clone git@github.com:SaritaPhD/End-to-End-Resume-Application-Tracking-System-LLM-.git
- cd End-to-End-Resume-Application-Tracking-System-LLM-
- Create a virtual environment: python -m venv venv
- source venv/bin/activate  # On Windows use `venv\Scripts\activate`
I- nstall the required packages: pip install -r requirements.txt

## Set up your Google API key:
- Create a .env file in the project root directory and add your Google API key:
GOOGLE_API_KEY=your_google_api_key

## Usage
- Run the Streamlit app: streamlit run app.py
- Open your web browser and go to http://localhost:8501.

- Enter the job description in the provided text area.

- Upload your resume in PDF format.

- Click on the "Submit" button to get a professional evaluation or the "Percentage match" button to get a percentage match evaluation.


![Alt text](<Screenshot 2024-07-25 at 5.22.19 PM.png>)