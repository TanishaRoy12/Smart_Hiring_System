# Smart_Hiring_System
A streamlined recruitment platform develop with Python, NLP, MySQL and Stremlit designed to connect talented candidates with top-tier organizations. The Smart Hiring System automates job applications, shortlisting, interview scheduling, and more.

## Features
- **Candidate Portal:**  
  - Apply for jobs with ease.  
  - Resume parsing and analysis.  
  - Track application status and view interview schedules.  

- **Company Portal:**  
  - Post job openings and manage applications.  
  - Shortlist candidates based on skills and experience.  
  - Schedule and conduct virtual interviews.  

- **Admin Dashboard:**  
  - Monitor platform activities.  
  - Manage user data and recruitments.  
  - Ensure platform compliance and efficiency.  

## Technologies Used
- **Frontend:** Streamlit (Python-based web framework).  
- **Backend:** MySQL for database management.  
- **Resume Parsing:** PyResparser.  
- **Email Service:** SMTP for sending notifications.  
- **Other Libraries:**  
  - `FPDF` for generating PDF files.  
  - `spacy` for natural language processing.  
  - `Pandas` for data manipulation.  

## Installation
1. Install dependencies:
pip install -r requirements.txt

2. Set up the database:
Create a MySQL database and import the necessary tables.
Update mysql.connector.connect credentials in the script.

3. Run the application:
streamlit run ano3.py

Usage
Navigate to the respective portals: Candidate, Company, or Admin.
Follow the on-screen instructions to create accounts, manage jobs, and view data.
