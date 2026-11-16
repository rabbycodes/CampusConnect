# Campus Connect: Found and Lost

Campus Connect is a web application that gives Southeast university students and staff one central place to report lost items and post items they have found. Users can submit reports with details, location, date, and a photo, then search and filter listings to find a match. Owners confirm ownership by answering a private verification question before contact details are shared. Administrators can moderate posts and remove misuse.

## Tech Stack
HTML, CSS, JavaScript, Python, Django, SQLite, Pillow, Git and GitHub

## Setup
1. Clone the repo: `git clone https://github.com/rabbycodes/CampusConnect.git`
2. Create a virtual environment: `py -m venv venv`
3. Activate it: `venv\Scripts\activate`
4. Install packages: `pip install -r requirements.txt`
5. Create the database: `python manage.py migrate`
6. Run the server: `python manage.py runserver`
