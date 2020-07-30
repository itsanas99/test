TogoAlumni backend SETUP
==============

## About

It uses: 

 - django framework 
   https://www.djangoproject.com/

 - django restframework
   https://www.django-rest-framework.org/

## Steps

### To start working on it:

#### 1- create virtualenv:<br/>
`on windows` python -m venv envname

#### 2- activate your virtualenv (from Powershell)<br/>
envname\scripts\activate 

#### 2- activate your virtualenv (from git bash)<br/>
cd envname/scripts<br/>
. activate

#### 3- upgrade pip <br/>
python -m pip install --upgrade pip

#### 4- clone this repo into your workdir<br/>
git clone https://gitlab.com/elomedah/togoalumni.git
cd togoalumni/alumni_back

#### 5- Install all the required packages <br/>
pip install -r requirements.txt

#### 6- migrate the database <br/>
python manage.py migrate

#### 7- run the developpement server <br/>
python manage.py runserver (by default it runs on localhost:8000)

#### 8- Start playing with the api at endpoints: <br/>
/api/membership/signup  <br/>
/api/membership/list  ## list all the users (login required) <br/>

That's it.  <br/>
But beware this is just the beginning of a great story

