# openai-API
Django application that integrates with the OpenAI API to generate natural language responses to user inputs. The application is designed to work with both web browsers, allowing users to interact with it in whichever way is most convenient for them.


The application comes with Login, Logout, and Sign up pages, which allow users to create accounts and access the full functionality of the app. Additionally, users have the option to remove their conversation with one click, ensuring that their privacy is protected.


Once a user inputs a message the web interface, the Django application uses the OpenAI API to generate a response, which is then sent back to the user via the same channel. The application's integration with the OpenAI API.


The code is written in Python, using the Django web framework and the OpenAI API for natural language processing. The repository includes all the necessary files to run the application, as well as documentation on how to set it up and use it.

Prerequisites:

Python >=3.7.1 
Git 
OpenAI API key 

Clone the repository 
Create Venv and Install dependencies by running : 
step1: Clone the repository

Run These commands

step2:pip install -r requirements.txt 

step3: python manage.py makemigrations 
step4: python manage.py migrate

step5: python manage.py runserver

Make sure you have assigned your openAI Api key in openapp/views.py in line.NO 19
