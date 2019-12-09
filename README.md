# Profiles REST API

Profiles REST API source.


Once SSH'd into your vagrant instance

### Navigate to the vagrant directoty

cd /vagrant

### Create your virtual environment

python -m venv ~/env

source ~/env/bin/activate

pip install -r requirements.txt


### Launch Django server

python manage.py runserver 0.0.0.0:8000
