
#### flask_demo
I started on flask basics

use `git clone https://github.com/James-Wachuka/flask_demo.git` to get the code

`cd` to `flask_demo`

create virtualenv 
`python virtualenv env
`
and activate the `venv` using `venv\Scripts\activate`

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
 
 drop the existing database `db.drop_all()`
 
 create tables `db.create_all()`

insert rows `db.session.add_all([admin_role, mod_role, user_role, user_jade, user_kelvin, user_moses])`

write to the database: `db.session.commit()` check `print(user_role.id)`
