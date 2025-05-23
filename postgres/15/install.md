sudo apt install postgresql postgresql-contrib

sudo systemctl start postgresql.service

sudo -i -u postgres
psql
\q

createuser --interactive
createdb docmanager;

user
docmanager