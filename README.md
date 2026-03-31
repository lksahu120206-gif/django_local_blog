# Django Blog Application

This is a blog application I built while learning Django. The goal of this project was to understand how real-world web applications are structured and how different features connect together.

## Features

* Create and manage blog posts
* Comment system
* Tagging using django-taggit
* Similar posts recommendation (based on tags)
* Most commented posts section
* Share posts via email (AJAX-based)

## What I Learned

* How Django models, views, and templates work together
* Using custom managers (`Post.published`)
* Working with QuerySets, annotations, and aggregation
* Handling forms and AJAX requests
* Structuring a project for scalability

## Tech Stack

* Python
* Django
* SQLite
* HTML, CSS
* JavaScript (Fetch API)

## How to Run

Clone the repo:

```
git clone <your-repo-link>
```

Go to project folder:

```
cd mysite
```

Create virtual environment:

```
python -m venv env
env\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

Run server:

```
python manage.py runserver
```

## Notes

This project is still a work in progress. I plan to add authentication and improve the UI in future updates.

## Author

Lalit Kishor Sahu
