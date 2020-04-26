# Backend

## How to run
### Ubuntu
1. ```cd backend```
2. ```python3 -m venv venv```
3. ```. venv/bin/activate```
4. ```pip install -r requirements.txt```
5. ```pip install flask```
6. ```flask run```

## generate requirements.txt
1. ```python3 -m venv venv```
2. ```pip freeze | grep -v "pkg-resources" > requirements.txt``` [Note](https://stackoverflow.com/a/40167445)


## docker
1. ```docker build -t backend:latest```

## directory structure
```
.
������ ...
������ docs                    # Documentation files (alternatively `doc`)
��   ������ TOC.md              # Table of contents
��   ������ faq.md              # Frequently asked questions
��   ������ misc.md             # Miscellaneous information
��   ������ usage.md            # Getting started guide
��   ������ ...                 # etc.
������ ...
```

## Note
[tutorial](https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)
