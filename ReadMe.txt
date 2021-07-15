
Navigate to the website deployed on heroku cloud through the below URL :
============================================================================

https://techblogpost.herokuapp.com/


(If the link doesnot work follow the below steps)
Instructions
=====================

Open the project file in cmd

Install a virtual environment with the below command :

		pip install virtualenv 

create a virtual environment with the below command :

		virtualenv (GiveName)   
		
		ForExample: virtualenv Testenv

activate virtual environment with the below command.

	source Testenv/bin/activate

install django with the below command.

	python -m pip install Django

install pillow with the below command.

	pip install pillow.

install crispyforms with the below command.

    pip install django-crispy-forms

Run project through the below command

	python manage.py runserver
	
Go in the browser and hit the local lost with : http://localhost:8000/