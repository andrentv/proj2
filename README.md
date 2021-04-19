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
#settings incluir import / alterar Debub=False / incluir host heroku / Middleware / static root and Staticfiles Storage / django_heroku bottom
git push heroku main

appdirs==1.4.4
apturl==0.5.2
asgiref==3.3.4
autopep8==1.5.6
awscli==1.18.111
blinker==1.4
botocore==1.17.22
Brlapi==0.7.0
certifi==2020.4.5.1
chardet==3.0.4
click==7.1.2
colorama==0.4.3
command-not-found==0.3
cryptography==3.0
cupshelpers==1.0
dbus-python==1.2.16
defer==1.0.6
distlib==0.3.1
distro==1.5.0
distro-info===0.23ubuntu1
django-crispy-forms==1.11.2
docutils==0.16
filelock==3.0.12
gyp==0.1
httplib2==0.18.1
idna==2.10
importlib-metadata==1.6.0
jeepney==0.4.3
jmespath==0.10.0
keyring==21.3.0
language-selector==0.1
launchpadlib==1.10.13
lazr.restfulclient==0.14.2
lazr.uri==1.0.5
louis==3.14.0
macaroonbakery==1.3.1
more-itertools==4.2.0
netifaces==0.10.4
oauthlib==3.1.0
olefile==0.46
pexpect==4.6.0
Pillow==7.2.0
protobuf==3.12.3
pyasn1==0.4.8
pycairo==1.16.2
pycodestyle==2.7.0
pycups==2.0.1
Pygments==2.3.1
PyGObject==3.38.0
PyJWT==1.7.1
pymacaroons==0.13.0
PyNaCl==1.4.0
pyRFC3339==1.1
python-apt==2.1.3+ubuntu1.3
python-dateutil==2.8.1
python-debian==0.1.37
pytz==2020.1
pyxdg==0.26
PyYAML==5.3.1
reportlab==3.5.47
requests==2.23.0
requests-unixsocket==0.2.0
roman==2.0.0
rsa==4.0
s3transfer==0.3.3
SecretStorage==3.1.2
simplejson==3.17.0
six==1.15.0
sqlparse==0.4.1
systemd-python==234
toml==0.10.2
ubuntu-advantage-tools==24.4
ubuntu-drivers-common==0.0.0
ufw==0.36
unattended-upgrades==0.1
urllib3==1.25.9
virtualenv==20.4.3
wadllib==1.3.4
xkit==0.0.0
zipp==1.0.0

# postgresql
# sudo -i -u postgres // psql -U antv
# sudo systemctl restart postgresql
# sudo nano /etc/postgresql/12/main/pg_hba.conf
# psql | \q | \list | \du | \password
# CREATE DATABASE <name>; #criar
# drop database <name>; #deletar
# ALTER ROLE 'user' PASSWORD 'novasenha';
# GRANT ALL PRIVILEGES ON DATABASE <data> to <user>;
