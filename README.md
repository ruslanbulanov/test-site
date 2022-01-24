# test-site

# Create env(in main folder Test):
python -m venv env
env\Scripts\activate

# Create database:
python manage.py makemigrations
python manage.py migrate

# Run project:
python manage.py runserver
