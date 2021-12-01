# Dec_Q1
Problem Description:-
Create a Django Project which manages the Task.it will contains User,Board,Task etc. Focus on Backend Design, Business logics and REST APIs .For reference please browse
https://trello.com/ . You need to sign up first for better understanding.

The tech stack required is Python3,Django. Preferred IDE is PyCharm to import the project directly. Postman tool to test the REST APIs and git.


Problem Breakdown 

To start the development a skelton repo for the project is provided at the github link –
https://github.com/kumarram1011/Dec_Q1/tree/taskmmt

Below are few points to consider:
The candidate should ensure the availability of Git, Python and Django on their system as part of the setup exercise. Then repo can be cloned into their local system through HTTPs or SSH. 
After cloning the project at your location, follow the below points:
	
	Create Virtual env (ubuntu)
		1. sudo apt install python3-venv
		2. python3 -m venv relevel_env
		3. cd relevel_env/
		4. source bin/activate
	Now quit this env location and jump to your working location/ Parent directory
	 
		
Install all dependencies using ‘pip install -r requirements.txt’
Now run your initial migrations with the command as:
	1. python manage.py makemigrations
	2. python manage.py migrate
	
	Note :- A. At very first since tehre is no any model in your projects so the 1st command will give you the resposne as "NO changes" but the 2nd command will configure you 				all inital setting like DB and all.
		B. At every satges while developing/implimenting the features please use both of the above command to reflect you changes in running/development server.

Run ‘python manage.py runserver’ to start the development server. Coding can now start and any changes done will be reflected instantly as hot reload. 

The hosted app can be checked on http://localhost:8000 on the browser.
