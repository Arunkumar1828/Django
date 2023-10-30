# Learning_Log Web Application using Django

The purpose of this project is to develop Django experience.

## Project Overview

This is a step-by-step guide for creating a Django web application that allows users to manage learning topics and entries. The application includes features such as user authentication, registration, user-friendly forms, and styling with Django-Bootstrap4. It will be deployed on PythonAnywhere.

## Prerequisites

Before you begin, ensure you have the following:
- Python and Django installed. You can install Django with `pip install Django`.
- A PythonAnywhere account for deployment.

## Steps

1. **Creating a Django Project, Starting an App, and Setting Up a Superuser**:
   - Create a new Django project:
     ```
     django-admin startproject projectname
     ```
   - Create a new app for your project:
     ```
     python manage.py startapp appname
     ```
   - Navigate to the project directory:
     ```
     cd projectname
     ```
   - Set up a superuser to manage the admin site:
     ```
     python manage.py createsuperuser
     ```

2. **Defining Models**:
   - Open the `models.py` file in your app.
   - Define models for learning topics and entries.

3. **Handling Routes, Writing Views, and Creating Templates**:
   - Define URL patterns in your app's `urls.py`.
   - Create views in your app's `views.py`.
   - Create HTML templates in the `templates` directory.

4. **Implementing User Authentication and Registration**:
   - Include `'django.contrib.auth'` in the `INSTALLED_APPS` setting.
   - Set up URLs and views for login, logout, and registration.

5. **Allowing Users to Add/Edit Topics and Entries**:
   - Create forms using Django's `forms.py` for user-friendly data input.
   - Implement views for adding and editing topics and entries, ensuring the user has proper permissions.

6. **Styling Pages with Django-Bootstrap4**:
   - Install the `django-bootstrap4` package:
     ```
     pip install django-bootstrap4
     ```
   - Include `'bootstrap4'` in the `INSTALLED_APPS` setting.
   - Use Bootstrap classes in your templates to style your pages.

7. **Deploying on PythonAnywhere**:
   - Sign up for a PythonAnywhere account if you haven't already.
   - Follow PythonAnywhere's documentation to deploy your Django project.

## Source

Based on "Python Crash Course: A Hands-On, Project-Based Introduction to Programming" by Eric Matthes (2nd edition, 2019).

