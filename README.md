# BibleTips

## Introduction

BibleTips enables users to get an overview of any notes they have taken related to the Christian bible. 

BibleTips has the following goals:
* Management of notes taken with topic and/or bible passage.
* Search by topic or bible passage.
* Display notes matching a particular topic or bible passage.
* Integration of sermon notes, personal bible reading and any other purpose for which notes were taken.

BibleTips has two components. An API server which manages the notes and can be used by the Web App or any other external tool 
and a sample web app which enables user interaction.

### API Server

The API Server is built on top of the FastAPI Framework: https://fastapi.tiangolo.com/

The current test API server can be run via the following command: 

`cd api
source .venv/bin/activate
fastapi dev main.py`

The API server is then reachable at the following address:
http://localhost:8000/

The Swagger documentation can be reached at the following URL:
http://localhost:8000/docs

### UI Web App

The Web App is built on top of the Django Framework:
https://www.djangoproject.com/

The current test Web App can be run via the following command:
`cd ui
source .venv/bin/activate
python3 manage.py runserver 8002`

The Web App is then reachable at the following address: 
http://localhost:8002/