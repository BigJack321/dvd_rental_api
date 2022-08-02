
# API for dvdrental database

This is an API made in a few hours, user can choose records from table via queries.

## Installation 


###First of all download the code, and extract "dvd_rental_flask.zip", then in your terminal window paste following commands (make sure you are in dvd_rental_flask directory!):

- `python3 -m venv .venv` - this piece of code creates virtual machine inside current directory
- `source .venv/bin/activate` - activate virtual machine, something like this should appear before your username in terminal:
![activated_venv](https://user-images.githubusercontent.com/96385701/182427011-c1acecfd-726f-49cc-ab50-ae4e25199bed.png)
- `pip3 install -r requirements.txt` - install all requirements in this txt file
And that's it in python for now.

###Next up you have to download postgreSQL, there is the link to postgreSQL install tutorial:

[install postgreSQL](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/)

###If you have postgreSQL installed, load dvdrental database:

[load database](https://www.postgresqltutorial.com/postgresql-getting-started/load-postgresql-sample-database/)

###To check if installation is ok you can try following this article:

[list tables](https://www.educba.com/postgresql-list-tables/)

###Now open new terminal window and change directory to dvd_rental_flask that you downloaded earlier, and paste:
- `source .venv/bin/activate` - activate virtual machine
- `export FLASK_APP=app.py`
- `export FLASK_ENV=development`
- `export DB_USERNAME="username"` - pass the username with required privileges
- `export DB_PASSWORD="password"` - pass password connected to the username 
- `flask run` - run flask application

###Copy the URL that appeard in your terminal window and paste it to new tab in your browser

![image](https://user-images.githubusercontent.com/96385701/182358039-92a6ee57-9ad9-45e1-affd-61dff6e811d2.png)

###Right now you can follow the **documentation** that appeared on the screen.

