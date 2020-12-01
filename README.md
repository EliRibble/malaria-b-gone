# Python: Getting Started

A barebones Flask app, which can easily be deployed to Heroku.

## Running Locally

Make sure you have Python 3.7 [installed locally](http://install.python-guide.org). To push to Heroku, you'll need to install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

Set up a virtual environment to hold your dependencies. How you do this depends on your system, but may be as simple as

```
python3 -m venv ve
source ve/bin/activate
```

Then install the dependencies for this project

```
pip install -r requirements
```

Then start up the development server

```
python app.py
```
