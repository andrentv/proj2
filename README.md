# proj2 - ecommerce 
# Nextjs - Django - Postgres

Install:
virtaulenv <name> 
source <name>/bin/activate
pip install Django
django-admin startproject <name>
python manage.py startapp <name>
python manage.py runserver
pip install psycopg2-binary
pip install djangorestframework
pip install python-decouple

python manage.py makemigrations
python manage.py migrate
Pizza - models and admin

python manage.py createsuperuser


Django Rest 
settings = django rest framework and insert code
serializer / view / urls (atention name of folder and dbase)

pip install django-cors-headers
alterações settings.py install apps/ middlaware/ code at bottom

deploy heroku
pip install django-on-heroku
pip install gunicorn whitenoise
heroku CLI


heroku login / confirmar com senha
pip freeze > riquirements.txt
pip install -r requirements.txt --upgrade
heroku git:remote -a <vacc-ecommercebackend> #inclui git remote
#settings incluir import heroku/os / alterar Debub=False / incluir host heroku / Middleware / static root and Staticfiles Storage / django_heroku bottom
git push heroku main

#Postgres
Criar servidor com as credenciais Heroku

#transferir dados
heroku run python manage.py makemigrations
heroku run python manage.py migrate
python manage.py dumpdata --natural-primary --natural-foreign > dump.json
commit again



# postgresql
# sudo -i -u postgres // psql -U antv
# sudo systemctl restart postgresql
# sudo nano /etc/postgresql/12/main/pg_hba.conf
# psql | \q | \list | \du | \password
# CREATE DATABASE <name>; #criar
# drop database <name>; #deletar
# ALTER ROLE 'user' PASSWORD 'novasenha';
# GRANT ALL PRIVILEGES ON DATABASE <data> to <user>;
