# MY_OCPP Server
### Simplest transfort draft (Reference: https://www.youtube.com/watch?v=cw8-KFVXpTE)

## Dev Environment setting and checking
```
$pwd
~/OCPP
$ virtualenv venv   
$ ls
venv/
$ source venv/scripts/activate
(venv)$ git clone https://github.com/jeongsooh/my_ocpp.git
(venv)$ ls
my_ocpp/  venv/
(venv)$ cd my_ocpp
(venv)$ ls
db.sqlite3  evsp/  manage.py*  ocpp16/
(venv)$ pip install channels
(venv)$ pip install djangorestframework
(venv)$ pip install requests
(venv)$ python manage.py runserver 
```
