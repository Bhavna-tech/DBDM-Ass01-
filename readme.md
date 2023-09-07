# Instructions to run on windows

# Folder Structure
D:.
|   app.py
|   dbquery.txt
|   readme.md
|   requirements.txt
|
+---instance
|       site.db
|
+---universityapp
|   |   forms.py
|   |   models.py
|   |   routes.py
|   |   __init__.py
|   |
|   +---instance
|   |       site.db
|   |
|   +---static
|   |       main.css
|   |
|   +---templates
|   |       advisorinfo.html
|   |       courseinfoform.html
|   |       departmentinfoform.html
|   |       index.html
|   |       instructorinfoform.html
|   |       layout.html
|   |       studentinfoform.html
|   |       teachesinfo.html
|   |       universitydata.html
|   |--------
-------------------------------------------

# Flask - Univeristy App

<!-- To run the App -->
# Install virtual environment package using:
`# pip install virtualenvwrapper-win`

# Firstly create virtual environment
# Create virtual env
`# mkvirtualenv univeristy`
`# workon univeristy`

# Install all modules from requirements.txt
`# pip install -r requirements.txt`

# Set app.py as FLASK_APP env var
`# set FLASK_APP=app.py` 

# database is stored in instance folder nothing need to be done there
# move to folder `FLASK` as it contains app.py 
# Run flask app 
`# python app.py`
# Open url in web browser
`http://localhost:5000/`

# dbquery.txt consists of sql queries need to be run as mentioned in question please refer that
# Path - D:\Flask\dbquery.txt

