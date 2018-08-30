### Create virtual environment
virtualenv venv 
source venv/bin/activate


### Download pip dependencies 
pip install -r requirements.txt


### set up DB
./manage.py makemigrations users 
./manage.py migrate users
./manage.py migrate



### List all superusers 
http://127.0.0.1:8000/api/v1/users/

### User login 
http://127.0.0.1:8000/api/v1/rest-auth/login/

### User logout -- doesnt work?
http://127.0.0.1:8000/api/v1/rest-auth/logout/


### Register New user
http://127.0.0.1:8000/api/v1/rest-auth/registration/


Tutorial:
https://wsvincent.com/django-rest-framework-user-authentication-tutorial/

