# django-project
Django - Web Development Tutorial from Djangogirls

## My First Django Project Running
- Setup Virtualenv
- Install Python, Django, Requirements, Git
- Settings: timezone, languange, path for static files, allowed hostname
- Setup Database
- Start Web Server
- Run Website: http://127.0.0.1:8000/

## Django Models
- Know about objects
- Create application - blog
- Create blog post model
- Create tables for models in your database

## Django Admin
- Import post model
- Create a superuser
- Login to Django admin
- Create posts

## Ready to Deploy
- Install git
- Create repository & push codes to GitHub
- Sign Up account & setup blog on PythonAnywhere
- Ready deploy web on PythonAnywhere

## Django URLs
- Create blog urls on blog/urls.py

## Django Views
- Create views function on blog/views.py

## Django Templates
- Create first template
    - Create directory blog/templates/blog
    - Create & customize HTML template file

## Django ORM and QuerySets
- Learn how Django connects to the database and stores data in it
- Learn about QuerySet & Django shell
- Learn about objects: view, create, filter, order

## Dynamic data in templates
- Connect models and templates

## Django Templates Tags
- Display post list template

## CSS Bootstrap on Django
- Install Bootstrap
- Learn static files in Django
- Create CSS folder & file

## Template Extending
- Create a base template

## Extend the Django application
- Create a template link to a post's detail
- Create a URL to a post's detail
- Add a post's detail view
- Create a template for the post details

## Django Forms
- Link to a page with the form
- Create form page url
- Create post_new view & template
- Saving the form
- Form validation
- Edit form
- Authenticated form

## The Tutorial Part 1 Done!
- Time to deploy
- Continue to tutorial extensions

## Site Improvements
- Save new posts as drafts
- Page with list of unpublished posts
- Add publish button
- Add delete post button

## Secure Your Website
- Authorizing add/edit of posts
- View login users
- Improving the layout
- Add details to show when we are logged in
- Now you have a blog where you:
    - need a username and password to log in,
    - need to be logged in to add, edit, publish or delete posts,
    - and can log out again.
    
## Create comment model
- Creating comment blog model
- Create tables for models in database
- Register Comment model in admin panel
- Make the comments visible
- Let the readers write comments
- Moderating comments: approve or delete
- Show the number of approved comments

## PostgreSQL Installation
- Install PostgreSQL on Ubuntu
- Create database: name, user, and password
- Update settings.py: DATABASES
- Installing PostgreSQL package for Python
    - pip install psycopg2
    - just little complicated
- Applying migrations and creating a superuser
- Try the application
    - run server
    - login
    - try to view/add/edit/delete posts & comments

## Deploy to Heroku

- Create requirements.txt file
- Create Procfile file
- Create runtime.txt file
- Create mysite/local_settings.py
- Modify mysite/settings.py
- Install Heroku CLI
- Login Heroku account
- Git commit
    - .gitignore local_settings.py
    