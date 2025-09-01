# MajorProject

Intelligent Resume Analysis and Job Fit Assessment System
📌 Overview

This project is an AI-powered Resume Analyzer and Job Fit Assessment System built with Streamlit.
It helps job seekers by:

Analyzing uploaded resumes (PDF format).

Matching resumes with relevant job roles using TF-IDF and KNN similarity.

Providing insights into skill gaps.

Suggesting learning resources to enhance employability.

Offering links to top job portals for applications.

🚀 Features

📄 Resume Analyzer – Upload multiple resumes (PDF), check page limits, and validate resume quality.

🤝 Job Matching – Get the top 5 best-fit job roles based on skills extracted from resumes.

📊 Visualization – Pie chart showing match accuracy with recommended jobs.

🎯 Career Enhancement – Discover courses, skill-building platforms, and resources.

🌐 Job Finder – Direct links to job portals (LinkedIn, Indeed, Naukri, etc.).

📬 Contact Section – Provides contact details for feedback or queries.

🛠️ Tech Stack

Frontend: Streamlit

Data Processing: pandas, numpy, nltk, re

ML/NLP: scikit-learn (TF-IDF, KNN), matplotlib (visualization)

PDF Handling: PyPDF2, PyMuPDF

Dataset: cleaned_file.csv (contains Job Titles & Skills for matching)

📂 Project Structure
├── analyzer.py        # Main Streamlit application
├── cleaned_file.csv   # Dataset with Job Titles and Skills
├── requirements.txt   # Dependencies
└── README.md          # Documentation (this file)

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer


Create virtual environment (recommended)

python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows


Install dependencies

pip install -r requirements.txt


Run the application

streamlit run analyzer.py

📊 Usage

Open the app in your browser (http://localhost:8501).

Navigate using the sidebar:

Home → Overview of the platform

About Us → Explore job titles and required skills

Resume Analyzer → Upload resumes & get matched jobs

Find Jobs → Links to popular job portals

Enhance Skills → Courses & resources

Contact Us → Feedback and queries

🤝 Contribution

Contributions are welcome!

Fork the repo

Create a new branch (feature-branch)

Commit your changes

Open a Pull Request

📧 Contact

Email: resumeanalyzerr@gmail.com

Phone: +91 7676346378
