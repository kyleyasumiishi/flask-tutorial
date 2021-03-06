# Flask Tutorial

## About

I followed the fantastic <a href="https://flask.palletsprojects.com/en/1.1.x/tutorial/#tutorial">Flask Tutorial</a> in the Flask Documentation to learn how to use the Flask framework to build web applications. This page contains instructions for installing the application, as well as the many resources I used and lessons I learned by completing this tutorial.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

Clone the repository
```
git clone https://github.com/kyleyasumiishi/flask-tutorial.git
```
Create a virtual environment to manage dependencies
```
python -m venv venv
cd venv\Scripts
source activate
```
Install dependencies
```
# cd into flask-tutorial directory
pip install -e .
```
Set environment variables
```
export FLASK_APP=flaskr
export FLASK_ENV=development
```
Initialize the database
```
flask init-db
```
Run the application
```
flask run
```

### Testing

Install pytest and coverage to run unit tests
```
pip install pytest coverage
```
Run the tests
```
pytest
```
Measure code coverage of tests
```
coverage run -m pytest
```