This is a flask blog that allows authentication, add, delete and edit blog posts. Also displays random quotes
>## Author: [El-rophi Skwaila](https://github.com/Elrophi/flask-quote)

---

>## Description
### This is a simple blog app that lets you create blog posts and read random quotes as well
---

## Technology Used: 
>Bootstrap

>Python

>Flask

---

>## Installation and setup locally
## Pre-requisites
- Python3
- Virtual environment
- bootstrap
- flask

---
>## Cloning and opening on compiler
#### On your terminal run

    $ git clone https://github.com/Elrophi/flask-quote.git
    $ cd user-story
    $ code .
##  Setting up the virtual environment and activating it
    $ python -m venv <name of virtual environment>
    $ source <name of virtual environment>/bin/activate
##  Install flask and modules needed using requirements.txt
       $ pip3 freeze install -r requirements.txt
       
## Creating the start.sh file to tun the app
 - Create a file and name it start.sh
 - in the file add this

       export SECRET_KEY=<you api key>
       python3 manage.py server