# Django REST framework JWT Authentication demo

## Get up and running locally

1. Clone this project into your local system.
    
    `git clone https://github.com/tirthyakamaldasgupta/django-rest-framework-token-authentication-demo.git`

2. A working version of Python3 should be installed on your system.

3. Create a virtual environment at the root of the project directory.

    3.1. On Windows

        `python -m venv <virtual_environment_name>`

    3.2. On Linux and Mac OS

        `python3 -m venv <virtual_environment_name>`

3. Activate the virtual environment.

    4.1. On Windows

        `<virtual_environment_name>\Scripts\activate`

    4.2. On Linux and Mac OS

        `source <virtual_environment_name>/bin/activate`

4. Install the required dependencies.

    `pip install -r requirements.txt`

5. Migrate the models.

    `python manage.py migrate`

6. Start the server

    `python manage.py runserver`

---

## Notes

1. For the purpose of the demo a library called 'djoser' has been used which provides readymade auth APIs.

2. For the purpose of the demo a SQLite file has been used as a database.

---

## Reference links

1. djoser- https://djoser.readthedocs.io/en/latest/getting_started.html