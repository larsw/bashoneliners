Setup
-----

Install required python modules:

    pip install -r requirements.txt

Create database (sqlite3), and admin account:

    python manage.py migrate

Start local website on localhost:8000

    python manage.py runserver


Local Settings
--------------

To override the default `settings.py` file in production, create a
`local_settings` file and pass it to `manage.py` using the `--settings flag`, like this:

    python manage.py migrate --noinput --settings=bashoneliners.local_settings


