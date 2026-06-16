## Smart Resume Parser

📄 An NLP-powered Resume Parser built using Python, SpaCy, Streamlit, PyMuPDF, and python-docx. This application extracts structured information from resumes in PDF and DOCX formats, including candidate details such as name, email, phone number, skills, and education.

## Project Overview

Recruiters often spend significant time manually reviewing resumes to identify suitable candidates. The Smart Resume Parser automates this process by extracting key information from resumes and presenting it in a structured format.

The application accepts PDF and DOCX resumes, processes the content using Natural Language Processing (NLP) techniques and regular expressions, and displays the extracted information through an interactive Streamlit interface.

## Features

✅ Upload resumes in PDF format

✅ Upload resumes in DOCX format

✅ Extract candidate name

✅ Extract email address

✅ Extract phone number

✅ Extract technical skills

✅ Extract education details

✅ Export results as CSV

✅ Export results as JSON

✅ User-friendly Streamlit dashboard

## Technologies Used
Technology	Purpose
Python	Core Programming
Streamlit	User Interface
SpaCy	Natural Language Processing
PyMuPDF	PDF Text Extraction
python-docx	DOCX Processing
Pandas	Data Handling
Regular Expressions	Pattern Matching

## Project Architecture

Resume Upload
      ↓
Text Extraction
(PDF/DOCX)
      ↓
Text Cleaning
      ↓
NLP Processing
(SpaCy + Regex)
      ↓
Information Extraction
      ↓
Structured Output
      ↓
CSV / JSON Export

## Project Structure

smart-resume-parser/
│
├── app.py
├── parser.py
├── skills.csv
├── requirements.txt
├── outputs/
└── README.md

## Installation

Clone Repository
git clone https://github.com/yourusername/smart-resume-parser.git
Move Into Project Directory
cd smart-resume-parser
Install Dependencies
pip install -r requirements.txt
Install SpaCy Language Model
python -m spacy download en_core_web_sm
Running the Application

Start the Streamlit application:

streamlit run app.py

Open the browser and visit:

http://localhost:8501
How It Works
Step 1: Upload Resume

The user uploads a PDF or DOCX resume.

Step 2: Text Extraction

The application extracts textual content using:

PyMuPDF for PDF files
python-docx for DOCX files
Step 3: Information Processing

The extracted text is processed using:

SpaCy NLP
Regular Expressions
Skill matching algorithms
Step 4: Information Extraction

The system identifies:

Name
Email
Phone Number
Skills
Education
Step 5: Export Results

Users can download extracted information in:

CSV format
JSON format
Sample Output
{
    "Name": "John Smith",
    "Email": "johnsmith@gmail.com",
    "Phone": "9876543210",
    "Skills": [
        "Python",
        "SQL",
        "Machine Learning",
        "Flask"
    ],
    "Education": [
        "B.Tech"
    ]
}
Skills Dataset Example
Python
Java
SQL
Machine Learning
Deep Learning
Flask
Django
AWS
Docker
Git
React
Future Enhancements
Resume Ranking System
ATS Score Calculation
Job Recommendation Engine
Candidate Shortlisting
OCR Support for Scanned Resumes
AI-Based Resume Analysis
Resume-Job Matching
Challenges Faced
Different resume formats
Inconsistent section headings
Skill identification accuracy
Processing scanned resumes
Extracting structured data from unstructured text
Learning Outcomes

Through this project, I gained practical experience in:

Natural Language Processing (NLP)
Resume Data Extraction
PDF and DOCX Processing
Streamlit Application Development
Data Export Techniques
Regular Expressions
Python Project Development
Screenshots
Home Page

Upload resume through Streamlit dashboard.

Extracted Information

Display candidate details in structured format.

Export Options

Download extracted data as CSV or JSON.

Author

Mithu Misra

Python Internship Project

License

This project is developed for educational and internship purposes only.

GitHub Repository Description
Smart Resume Parser built using Python, SpaCy, Streamlit, and PyMuPDF to automatically extract candidate information such as skills, education, email, and phone number from PDF and DOCX resumes.
GitHub Topics
python
streamlit
spacy
nlp
resume-parser
pdf-processing
machine-learning
python-project
internship-project
data-extraction
