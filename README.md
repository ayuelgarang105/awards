# AWARDS

Author:[Gabriel Ayuel](https://github.com/ayuelgarang105)  
  
# Description  

An application like Awwards that allows a user to post a project he/she has created and get it reviewed by his/her peers.


## User Story  
As a user, I would like to:

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects 
* View projects overall score
* View my profile page 

  
## Setup and installations
* Fork the data .
* git clone the gallery repo.
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`



## Getting started

### Prerequisites
* python3.6
* virtual environment
* pip

#### Clone the Repo 
```bash
git clone https://github.com/ayuelgarang105/awards.git
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3 -m venv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY='**'
DEBUG=True
DB_NAME='****'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3 manage.py check
python manage.py makemigrations gallery
python3 manage.py sqlmigrate gallery 0001
python3 manage.py migrate
```

#### Run the app
```bash
python3 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)



## Testing the Application
`python manage.py test instaClone`
        
## Technologies Used

* [Python3.8](https://docs.python.org/3/)
* Django 
* Postgresql 
* Boostrap
* HTML

## Contact Information   
Please email me at ayuelgarang105@gmail.com for any question or contributions,
  
## License 

[MIT](LICENSE.md)  <br>
Copyright © by Gabriel Ayuel 
