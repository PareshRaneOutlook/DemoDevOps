>>This is sample webapp which showcase ML model deploy on Django and React. Please see below given url to understand ML model use case with Random Forest Classification on IRIS dataset
>>https://blog.devgenius.io/learning-random-forest-classification-using-iris-dataset-eeb930612e0e



 >> install git  (https://git-scm.com/download/win)

	git config --global user.email "your account email id"


>> Install MySQL and cread database "predictiondb" and user  with following credentials
        'USER': 'mysql',
        'PASSWORD': 'mysql',
		
>> Install Python 3.12.4

	https://www.python.org/downloads/release/python-3124/

>> Under Project folder  Install Virtual Environment

	--On Windows
 	pip install virtualenv
	python3 -m virtualenv localPythonEnv
	localPythonEnv\Scripts\activate
	
 	--On Ubuntu
 	python3 -m pip install virtualenv
	python3 -m venv localPythonEnv
	source localPythonEnv/bin/activate

>> Install Django and respective libraries from your project folder

	pip install -r requirements.txt 

>> From "django app" folder run

	python manage.py migrate	
 
 	python manage.py createsuperuser  // create User : admin Password :admin_password
 	
	python manage.py runserver

		
>> Install node18.20


>> From Frontend\react run
npm start


