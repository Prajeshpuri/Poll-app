# Poll App
Django first app

---

## About

This is a Django tutorial project which was made for the purpose of learning Django. Django is a Python-based free and 
open-source web framework, to learn Django and make a similar poll app refer 
![Official Django Tutorials](https://docs.djangoproject.com/en/3.0/intro/tutorial01/).

---

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Prerequisites
`python== 3.5 or up and django==3.0 or up`

#### Installing
> open terminal and type

`git clone https://github.com/Prajeshpuri/Poll-App.git`

#### To migrate the database open terminal in project directory and type
```
python manage.py makemigrations
python manage.py migrate
```

#### To use admin panel you need to create superuser using this command 
`python manage.py createsuperuser`

#### To run the program in local server use the following command 
`python manage.py runserver`

#### Then go to [LocalHost](http://127.0.0.1:8000/polls) in your browser
