

About the Project 🥱

Scope 😲

Converts resume data into structured tabular format for analytics purposes.

Provides recommendations, predictions, and scores to help users improve their resumes.

Increases user engagement and traffic to the tool.

Helps colleges analyze students' resumes before placements.

Provides analytics on job roles users are searching for.

Continuously improves based on user feedback.

Tech Stack 🍻

Frontend

Streamlit

HTML

CSS

JavaScript

Backend

Streamlit

Python

Database

MySQL

Modules

pandas

pyresparser

pdfminer3

Plotly

NLTK

Features 🤦‍♂️

Client:

Extracts location and miscellaneous data.

Parses resume for basic info, skills, and keywords.

Recommends additional skills, predicted job roles, courses, certifications, resume tips, and interview guidance.

Provides an overall resume score.

Admin:

Stores and displays applicant data in tabular format.

Allows data export to CSV.

Provides analytics using pie charts (e.g., ratings, experience level, resume scores, user count, locations).

Manages user feedback and ratings.

Setup & Installation 👀

Clone the repository:

git clone https://github.com/rajatyadav011/AI-Resume-Analyzer.git

Create and activate a virtual environment:

python -m venv venvapp
cd venvapp/Scripts
activate

Install dependencies:

cd ../..
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm

Set up the MySQL database and update credentials in App.py.

Run the application:

streamlit run App.py

Known Issues 🤪

If GeocoderUnavailable error occurs, check your internet connection.

Usage

Upload a resume and view analysis, recommendations, and insights.

Test the system using the sample resume in the Uploaded_Resumes folder.

Admin credentials: admin / admin@resume-analyzer

Roadmap 🛵



Contributing 🤘

Pull requests are welcome. Open an issue for major changes.

For full project details, email me.

Acknowledgement 🤗

Special thanks to various open-source projects and contributors that made this possible.

Preview 👽

Client Side



Admin Panel



Built with 🤍 AI RESUME ANALYZER by Rajat Yadav

