# Django tutorial 

This repo follows the tutorial by the django team documented here https://docs.djangoproject.com/en/5.0/. 

The tutorial, helps one with the creation of a basic poll application.

It’ll consist of two parts:
- A public site that lets people view polls and vote in them.
- An admin site that lets you add, change, and delete polls.

<img width="1074" alt="image" src="https://github.com/j2moreno/django-tutorial/assets/13912964/d2d99c16-5c48-4493-8c69-aacc9ca00f61">

## Install conda environment

```
conda env create -f environment.yml
```

## Run Sever

```
cd django_tutorial
python manage.py runserver
```

Go to http://127.0.0.1:8000/polls/ to see application.

## Improvements

- Made sure that only questions with at least 1 choice was dispalyed
  - tests were created to verify
- Improvements to HTML/CSS
- Cretaed base.html as to not repeat code in HTML  


