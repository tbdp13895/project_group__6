# project_group__6

# HOSPITAL DATA ANALYSIS

Our Python web application is designed to analyze hospital data stored in an SQLite database. It provides a user-friendly interface to view information about hospitals, including various attributes such as provider ID, hospital name, address, city, state, ZIP code, and more.


## Project Structure:

PROJECT_GROUP__6/

├── data collection/
│   └── collect.ipynb
|
├── data processing/
│   └── hospital.csv
│   └── process.ipynb
|
├── database/
│   └── hospital.db
│
├── website/
|   └── templates/
│       ├── about.html
│       ├── data.html
│       └── index.html
│       └── hos.py
|
|
├── .gitinore
├── README.md
└── requirements.txt

- database/: Directory containing the SQLite database file hospital.db, which stores the hospital data.
- templates/: Directory containing HTML templates for the web pages.
- about.html: Template for the About page.
- data.html: Template for the Data page.
- index.html: Template for the Index page.
- hos.py: Python script containing the Flask application code.
- README.md: Markdown file providing information about the project.
- requirements.txt: Text file listing the required Python packages and their versions

## Set up:
1. Clone the repository:
git clone https://github.com/tbdp13895/project_group__6

2. Install the required dependencies:
pip install -r requirements.txt

3. Usage:
- Start the Flask web server: python hos.py
- Open your web browser and go to http://localhost:5000.
- Navigate to different pages to explore the hospital data.