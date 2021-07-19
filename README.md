# django-venv

python -m venv venv

venv\scripts\activate

pip freeze > requirements.txt # records an environment's current package list into requirements.txt

pip install -r requirements.txt # requirements.txt in root directory
