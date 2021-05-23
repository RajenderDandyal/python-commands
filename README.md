# python-commands
python commands 

* import pdb; pdb.set_trace()
* Kill running process
* sudo lsof -i :portNumber

* python3 -m venv tutorial-env
* source tutorial-env/bin/activate
* deactivate

* pip3 install requests
* pip3 install requests==2.6.0
* pip install --upgrade requests

* pip3 list
* pip freeze
* pip3 freeze > requirements.txt
* pip3 install -r requirements.txt



# Maintaining env through virtualenv
* pip3 install virtualenv
* cd to project folder
* python3 --version
* virtualenv venv --python=python3.8.5
* source venv/bin/activate
* Deactivate

/////////pipenv/////////
* Pipenv install lib
* Piping shell
* deactivate

#
******************************
********* anaconda ***********
******************************
* conda env create -f environment.yml
* conda activate pyfinance
* Source activate pyfinance
* conda deactivate
* jupyter notebook
* Conda update pandas
* Conda update --all
* Conda remove --name pandas_tuts
* conda create --name quant python=3.7
* conda activate quant
* conda deactivate
* conda info --envs
* Conda install spyder
* spyder
* spyder --new-instance

//////////////////////////////////////
////////// python/////////////////////
//////////////////////////////////////
* python3 -m venv env -- carets vena
* source env/bin/activate  activate vent
* Deactivate -- deactivate vena
* pip3 install -r requirements.txt
#
////////////////////////////////////
//////////// django ///////////////
//////////////////////////////////
* django-admin startproject profile_project .
* python manage.py startapp profile_api
* python manage.py runserver
* python manage.py migrate
* python manage.py makemigrations … before that add to installed app in settings.py

* python manage.py createsuperuser
* import pdb; pdb.set_trace()
* python manage.py collectstatic


////////////////////////////////////
//////////// postgres //////////////
////////////////////////////////////

\password postgres(user)
CREATE DATABASE btredb OWNER postgres(user)
\l == list databases with owner

pip install psycopg2
pip install psycopg2-binary
