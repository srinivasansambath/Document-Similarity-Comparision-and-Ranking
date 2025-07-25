# Document-Similarity-Comparision-and-Ranking
Talent Match AI - Web App Designed for GenAI Designathon (Hackathon)

About:
Talent Match AI is a Streamlit-based AI web app designed for recruiters and hiring managers. 
It compares Job Descriptions (JDs) with consultant resumes using semantic embeddings to identify top matching consultants.

Features:
- Upload JDs and resumes in PDF or ZIP format
- Extracts and compares textual content using semantic similarity
- Highlights top 3 matching candidates
- Sends automated email to AR requester with best matches
- Tracks match status in an intuitive dashboard

Powered by:
- all-MiniLM-L6-v2 from Sentence Transformers for semantic comparison
- PyPDF2 for extracting text from PDFs
- SQLAlchemy + SQLite for persistent tracking
- Streamlit for a clean web interface

Software Required:
- Visual Studio Code
- Python 3.13.5
- Web Browser

Commands:
Run the following commands in your terminal 

pip install streamlit PyPDF2 sentence-transformers pandas sqlalchemy scikit-learn matplotlib

--This command installs all necessary libraries for running the JD Matcher application.

streamlit run app.py

--This command is to run the application

libraries details:

- streamlit -- Web UI
- PyPDF2 -- PDF text extraction
- sentence-transformers -- for matching
- pandas and matplotlib --  datatables + coloring 
- sqlalchemy -- DB
- fpdf -- used for generating sample PDF's





