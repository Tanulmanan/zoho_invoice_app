# Qjango - A Qux Django project template

## Getting started

### FILE: .env

Create a `.env` file in project and add the following ENV vars as needed. Start without DB_TYPE and use db.sqlite3 until you are sure about the database you wish to use.

```
└── dir:project
    └── file:.env
        ├── DJANGO_SECRET_KEY="thisisnotasecretkey"
        ├── DJANGO_DEBUG=true|false
        ├── DJANGO_DEBUG=servername,servername,servername
        ├── DB_TYPE="mysql"
        ├── DB_NAME=
        ├── DB_HOST
        ├── DB_PORT
        ├── DB_USERNAME
        ├── DB_PASSWORD
        ├── ATHENA_NAME
        ├── ATHENA_USERNAME
        ├── ATHENA_PASSWORD
        └── ATHENA_DB_PATH
        
```


