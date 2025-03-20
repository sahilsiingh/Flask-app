# REQUIREMENT
 
Flask
Flask-SQLAlchemy
Flask-Migrate
psycopg2-binary
python-dotenv

#READ - ME

Clone the repository and install required dependencies:  
```sh
git clone <repo-url> && cd <repo-name>
python -m venv venv && source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

CREATE DATABASE flask_auth_db; # SQL
CREATE USER flask_user WITH ENCRYPTED PASSWORD 'yourpassword';
GRANT ALL PRIVILEGES ON DATABASE flask_auth_db TO flask_user;
SQLALCHEMY_DATABASE_URI = "postgresql://flask_user:yourpassword@localhost/flask_auth_db"


# CREATE A TEMPLATE FOLDER IN PROJECT DIRECTORY
- HTML PAGES 
> registration
> login
> dashboard

# flask install all required libraries
> define host id for postgresql
> setup backend and frontend of html pages by linking.


