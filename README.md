# Tweet Scheduler

- Schedule and automate your tweets
- `Google Sheets` is used as database to store all the tweet data like content, time, and whether it is posted or note.
- The web app is deployed in `Heroku`
- We are using `tweepy` for accessing Twitter API and `gspread` for google sheets API

## Technology used

### 1. [Flask](https://flask.palletsprojects.com/en/1.1.x/)

- Flask is a micro web framework written in Python.
- It is classified as a microframework because it does not require particular tools or libraries.
- It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions
- To know more about Flask, Visit this [site](https://pythonbasics.org/what-is-flask-python/)

#### Installation

##### MACOS/ Linux

```python
mkdir myproject
cd myproject
python3 -m venv venv
. venv/bin/activate
pip install flask
```

##### Windows

```python
mkdir myproject
cd myproject
py -3 -m venv venv
venv\Scripts\activate
pip install flask
```

## Run flask in development server: `FLASK_APP=main.py FLASK_ENV=development flask run --port 8080`

### 2. [Heroku](https://www.heroku.com/)

- Heroku is a cloud platform that lets companies build, deliver, monitor and scale apps — we're the fastest way
  to go from idea to URL, bypassing all those infrastructure headaches.
- [Install Heroku](https://devcenter.heroku.com/articles/heroku-cli)

### 3. [Tweepy](https://www.tweepy.org/)

- An easy-to-use Python library for accessing the Twitter API.
- [Twitter API Access](https://developer.twitter.com/en)
- [Tweepy Installation Guide](https://docs.tweepy.org/en/stable/install.html)

### 4. [gSpread](https://docs.gspread.org/en/latest/)

- a Python API for Google Sheets.
- For more info on how to access google sheets and use gspread. Follow [this](https://github.com/d-cryptic/access-google-sheets-python)
- The google sheet used in this project: [View here](https://docs.google.com/spreadsheets/d/1hh9aKlo8aqh_92Y47JTBAI5j2bZOF9x0nN6UIk-tIqk/edit?usp=sharing)

### 5. [gUnicorn](https://gunicorn.org/)

- Productionr ready server

### 6. [CRON Jobs](https://cron-job.org/en/)

## For Frontend

1. HTML
2. CSS
3. Bootstrap
4. Javascript
