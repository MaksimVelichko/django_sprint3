cd django_sprint3

python -m venv venv

source venv/Scripts/activate

python -m pip install --upgrade pip

pip install -r requirements.txt

python manage.py migrate

python manage.py loaddata db.json

python manage.py runserver

http://127.0.0.1:8000/
