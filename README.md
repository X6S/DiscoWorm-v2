# README

This discord `worm` joins every server invite found.
 
Collects:
 
- Server name
- Server ID Code
- Name and ID of the people and bots in the server

## General overview

This program has 3 parts : 
- The worm (Discoworm.py)
- The server (Django)


## How to ...?

**Launch the server**
``` bash
cd siteweb/
python3 manage.py runserver
```

**Create admin user:**
``` bash
cd siteweb/
python3 manage.py createsuperuser
```  

**Make migration (to update the data model):**
``` bash
python3 manage.py makemigrations
python3 manage.py migrate
```

**Launch:**
- Start the server
- Then: 
``` bash
# Setup env
export DISCORD_TOKEN=<your_token>
# or edit ver/.env

python3 ver/Discoworm.py
```
