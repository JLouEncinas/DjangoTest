# Set up Instructions

## create virtual environment
1. download python
2. run this command `pip install virtualenv`
3. then this command `virtualenv venv`
4. activate virtual environment `venv\Scripts\activate`
5. install dependencies as stated below

## to install dependencies:
` pip install -r requirements.txt`


## migrate to db
`python manage.py migrate`

## run django
`python manage.py runserver`