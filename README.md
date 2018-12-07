#Info

IP: `138.68.105.124` Port: `2200`
URL: `http://138.68.105.124`

#Software installed
- postgresql
- apache2
- libapache2-mod-wsgi
- pip
- psycopg2

#Changes made
- Disabled password based login
- Changed ssh port from 22 to 2220
- Setup grader user and added him to sudoers
- Setup ssh connection for grader
- Setup the catalog as a wsgi application to be hosted on apache2
- Setup postgresql database and user
- Disabled remote connection to the db

#Third party resources
https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-against-automated-attacks
http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/#installing-mod-wsgi
