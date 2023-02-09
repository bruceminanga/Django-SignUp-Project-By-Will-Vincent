# Django SignUp Project By Will Vincent

To create a sign up page we will need to make our own view and url. Let's begin!

**Steps**
1. django-admin startproject authentication . Command To create project called authentication
2. python manage.py startapp accounts. Command to create a dedicated app called accounts
3. Register app with django. Anytime you want to use a new app inside of a Django project, you need to register it in the settings.py file. Add accounts to the installed_apps in you settings.py
4. Add pathpath('accounts/', include('accounts.urls')) to authentication urls.py
5. Adding urls.py. The startapp does not automatically generate a urls.py file in the new app that it creates. Create urls.py file in your accounts folder.
6. Define your view function in accounts/views.py
7. Create a template folder and create another folder called accounts which should have signup.html file.
8. Direct template in your settings.py

I learned this Project from https://learndjango.com/tutorials/django-signup-tutorial


