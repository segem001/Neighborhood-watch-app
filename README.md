# NeighHood-App
#### Application for users to join and find the posts about their neighbourhood.
####  **Kiprono Dominic Segem**

## Description
This is an app that allow users to be updated on what is happenning on their neighborhoods

## Project live site
  This is the live .()
 
 
 
## Features
* User can log in to application and view other peoples posts.
* A user can join neighborhood.
* A user can upload posts and edit their profile.
* Admin can regulate images uploaded by deleting from the admin dashboard as well as completely close a users account.







## Setup/Installation requirements
1.Clone or download and unzip the repository from github,https://github.com/johnopana/NeighHood-App.git

2. Activate virtual environment using python3.6 as default handler virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate

3. Install dependancies that will create an environment for the app to run pip3 install -r requirements.txt
4. Create the Database
- psql
- CREATE DATABASE baba;

4. Create .env file and paste paste the following filling where appropriate:

-SECRET_KEY = '<Secret_key>'
-DBNAME = 'baba'
-USER = '<Username>'
-PASSWORD = '<password>'
-DEBUG = True
5. Run initial Migration
-python3.6 manage.py makemigrations instagram
-python3.6 manage.py migrate
6. Run the app
-python3.6 manage.py runserver
-Open terminal on localhost:8000



## Technologies Used
* PYTHON 3.6
* DJANGO FRAMEWORK
* BOOTSTRAP
* CSS
* POSTGRESS

## Prerequisite
* PYTHON 3.6
* DJANGO FRAMEWORK
* PYTHON VIRTULENV
* POSTGRESS
## Support and contact details
contact me @ johnopana2016@gmail.com
### License
The project is under[MIT license](LICENSE)
Copyright &copy; 20120.All rigths reserved
  