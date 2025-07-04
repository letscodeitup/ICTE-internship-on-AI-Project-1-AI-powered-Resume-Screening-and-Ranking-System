# AICTE-internship-on-AI-Project-1-AI-powered-Resume-Screening-and-Ranking-System
AICTE Internship on AI: Transformative Learning  with  TechSaksham – A joint CSR initiative of Microsoft &amp; SAP

# AI Resume Screening & Candidate Ranking System

## Overview
This project is an AI-powered resume screening system that ranks resumes based on their similarity to a given job description. It extracts text from PDF resumes, computes TF-IDF scores, and calculates cosine similarity to rank candidates.

## Features
- Upload multiple PDF resumes.
- Extracts text using `PyPDF2`.
- Computes similarity scores using `TfidfVectorizer` and `cosine_similarity`.
- Displays ranked resumes with similarity scores.
- Built using `Streamlit` for an interactive UI.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip

### Install Dependencies
Run the following command to install the required packages:
```sh
pip install streamlit pandas PyPDF2 scikit-learn
```

## Usage
### Running the Application
Run the following command in your terminal:
```sh
streamlit run your_script.py
```
### Steps
1. Enter the job description in the text area.
2. Upload multiple PDF resumes.
3. The system ranks resumes based on their similarity to the job description.
4. View the ranked results in a table format.

## File Structure
```
|-- your_script.py  # Main application file
|-- requirements.txt  # List of dependencies
|-- README.md  # Project documentation
```

## Contributing
Feel free to fork the repository and submit pull requests with improvements!

## Contact
For any inquiries, reach out to [aarushi.sharma1227@gmail.com](aarushi.sharma1227@gmail.com).
