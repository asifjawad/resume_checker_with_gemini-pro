# Smart ATS: Enhancing Resumes with ATS Evaluation

## Overview
The Smart ATS (Application Tracking System) is a Python script designed to assist job seekers in improving their resumes. It leverages cutting-edge technologies and techniques to evaluate resumes against specific job descriptions. Here’s what each component does:

## Back-End Logic:
The script imports essential libraries, including `streamlit`, `google.generativeai`, `os`, `PyPDF2`, and `dotenv`.
It configures the Google Generative AI API key using environment variables.
Defines functions for generating responses and extracting text from uploaded PDF resumes.

## Streamlit Web App:
The web application, accessible via a browser, is titled **Smart ATS**.
Users interact with the app through a simple interface.
Key features include:

## Job Description Input: Users can paste the job description (JD) into a text area.
- **Resume Upload**: Users can upload their resume in PDF format.
- **Submit Button**: Upon clicking “Submit,” the app processes the resume and provides an ATS evaluation.
- **ATS Evaluation** Process: The ATS evaluates the uploaded resume based on the provided JD.

It considers the competitive job market and aims to provide valuable insights.
The evaluation includes:

- Matching Percentage: The degree to which the resume aligns with the JD.
- Missing Keywords: Identification of keywords or skills absent from the resume.
- Profile Summary: A concise summary of the candidate’s qualifications.

## How It Works

- **Input JD**: Users paste the job description into the designated text area.
- **Upload Resume**: Users upload their resume in PDF format.
- **Evaluation**: The ATS processes the resume, assesses its compatibility with the JD, and generates a structured output.


Remember to customize the JD and resume input for accurate results. Whether you’re a seasoned professional or just starting your career, the Smart ATS can help you optimize your resume for success! 🌟📄💼