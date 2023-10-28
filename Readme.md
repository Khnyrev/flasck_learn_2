Оплата не завелась из за конфликтов Flask 2.2.3 и cloudipsp 1.0.4 (нужно вернуться и разобраться)

FLASK_APP = main.py
FLASK_ENV = development
FLASK_DEBUG = 0
In folder /Users/alksejhnyrev/PycharmProjects/flaskProject
/Users/alksejhnyrev/venv/bin/python -m flask run 
Usage: python -m flask run [OPTIONS]
Try 'python -m flask run --help' for help.

Error: While importing 'main', an ImportError was raised:

Traceback (most recent call last):
  File "/Users/alksejhnyrev/venv/lib/python3.9/site-packages/flask/cli.py", line 219, in locate_app
    __import__(module_name)
  File "/Users/alksejhnyrev/PycharmProjects/flaskProject/main.py", line 3, in <module>
    from cloudipsp import Api, Checkout
ModuleNotFoundError: No module named 'cloudipsp'


Process finished with exit code 2
