# URL Shortener Web Application

A basic URL Shortener built using Flask and SQLAlchemy ORM.  
The application allows users to shorten long URLs, store them in a database, and view previously shortened URLs.

## Features
- Shortens long URLs
- Validates URLs before shortening
- Stores original and shortened URLs in database
- Redirects short URL to original URL
- History page to view all URLs

## Tech Stack
- Python
- Flask
- SQLAlchemy ORM
- SQLite
- HTML, CSS

## How to Run
pip install flask flask_sqlalchemy  
python app.py  

Open browser:  
http://127.0.0.1:5000/

## Project Structure
- app.py
- models.py
- templates/
- static/
- database.db
- orm_sqlalchemy.ipynb
