https://img.shields.io/hackage-deps/v/flask

##### flask_demo
I started on flask basics

use `git clone https://github.com/James-Wachuka/flask_demo` to get the code

`cd` to `flask_demo` and activate the `venv` using `venv\Scripts\activate`

install dependencies:

`pip install -r requirements.txt`

Run the app:

`set FLASK_APP=hello.py`

`set FLASK_DEBUG=1`

`set FLASK_ENV=developmet`


working out the database:

`CTRL+C` to stop a running app

 enter into flask shell ` flask shell`
 
 `import hello`
 
 `from hello import db`
 
 created tables `db.create_all()`

insert rows `db.session.add_all([admin_role, mod_role, user_role, user_jade, user_kelvin, user_moses])`

write to the database: `db.session.commit()` check `print(user_role.id)`
