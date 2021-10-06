## 實作內容
建立一個flaskr的應用服務，若要建立新的服務可以參考

- activate venv
```
$ cd  flaskr
$ . venv/bin/activate
```

Install the Project
```
$ pip install -e .
```

- run flask
```
$ set FLASK_APP=flaskr
$ set FLASK_ENV=development
$ flask run
```

- test flask
```
127.0.0.1/hello
```

Running Tests
```
$ python -m pytest -vv
$ pytest
$ coverage run -m pytest
$ coverage report
$ coverage html
```

## 參考
https://flask.palletsprojects.com/en/2.0.x/tutorial/factory/