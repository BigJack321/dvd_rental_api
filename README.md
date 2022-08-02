
# API for dvdrental database

This is an API made in a few hours, user can choose records from table via queries.

## Installation 

To run this app you need to ensure that you have **flask** and **psycpog2** downloaded on your virtual machine. You also need to download dvd rental database and create database user with priviliges.

Your virtual environment should be created inside project directory.

Steps you need to take to launch app, after your restarted your pc or started a new session:
1. Type all of thoose into your terminal on linux/macOS
- `source .venv/bin/activate`
- `export FLASK_APP=app.py`
- `export FLASK_ENV=development`
- `export DB_USERNAME="username"`
- `export DB_PASSWORD="password"`
In place of `"username"` and `"password"` you should pass username of your user and password.
2. When you typed all those commands, now you can start flask app:
- `flask run`
- copy the URL that appeard in your terminal window
![image](https://user-images.githubusercontent.com/96385701/182358039-92a6ee57-9ad9-45e1-affd-61dff6e811d2.png)

![image](https://user-images.githubusercontent.com/96385701/182358555-46a172f7-b4b9-4edd-9e1a-9e298e4b19d1.png)


### Links to installation

[dvdrental.zip](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)

[flask installation and virtual environment setup](https://flask.palletsprojects.com/en/1.1.x/installation/)

### How your directory should look like after instalation

![image](https://user-images.githubusercontent.com/96385701/182354937-7dbdf0f4-3219-45e5-94bc-59c5e7052b51.png)

## How to form queries

You can find documentation when you correctly run flask app, by clicking on *Documentation* header on base.html site.

