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
(venv)$ ls my_ocpp
db.sqlite3  evsp/  manage.py*  ocpp16/
(venv)$ pip install channels
(venv)$ pip install djangorestframework
(venv)$ pip install requests
(venv)$ code .
```
VS Code가 실행되면 터미널에서 다시 가상환경 활성화 후 Application 구동으로 확인
```
$ ls
my_ocpp/  venv/
$ source venv/scripts/activate
(venv)$ cd my_ocpp
(venv)$ python manage.py runserver 
```
