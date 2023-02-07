# How-To-Sign-Up-And-Log-In-Users-With-Django

First, we’ll set up the url patterns and routes that we need, then we’ll configure the needed view functions. In the view functions, we’ll make use of two really cool classes that Django offers. Those are the UserCreationForm and the AuthenticationForm classes. These two classes provide a way to scaffold out the entire sign up and login configuration of the forms to handle these tasks, with validation built right in.

**Steps**
1. django-admin startproject authentication .
2. python manage.py startapp accounts


