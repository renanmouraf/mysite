python3 -m venv venv

source ./venv/bin/activate

pip install -r requirements.txt

Create a user 'blog' and a database 'blog' on Postgresql

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

Open: http://localhost:8000/blog/
