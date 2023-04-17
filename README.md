# Foyer: Backend system

## Run server
### To run the commands python and its utilitarians must be in Path
 1. Create a virtual environment running `python -m venv C:\${path\to\project\root\folder}\foyer-env`
 2. Activate the virtual environment running `C:\${path\to\project\root\folder}\foyer-env\Scripts\activate"`
 3. Install dependencies running `pip install -r "requirements txt"`
 4. Run the Django application using `python manage.py runserver`
 5. The server will be running on [http://localhost:8000/graphql](http://localhost:8000/graphql)

## Database details

In order to connect with remote database the host and credentials are the following:

    - Host: `foyer-db.c9nvwxa5rwfa.us-east-2.rds.amazonaws.com` 
    - Username: `admin`
    - Password: `Foyer123#`