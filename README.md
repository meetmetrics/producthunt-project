# Product Hunt Project - Udemy

> PUBLIC Repo no passwords or secrets

## Requirements
- python3
- django 2.2.13
- psycopg2-binary (2.8.5)
- Pillow (7.2.0)

- postgres database



## Settings
2 variante:
- adaugare "secrets" in virtualenv activate
- in `settings.py` dar fara commit in repo

1. In `bin/activate` la sfarsitul fisierului
- Unix/Linux/MacOS (activate):

```bash
# activate:
export SECRET_KEY="blbabb32#%$@$#%$^$#^"
export DJANGO_SETTINGS_MODULE="producthunt.settings.local"

export DBNAME="dbname"
export DBUSER="dbuser"
export DBPASS="password"

export MAILCHIMP_API="--hidden--"
export MAILCHIMP_LIST_ID="--hidden--"
```

- Windows (`activate.bat`)

```cmd
# activate.bat:
set "SECRET_KEY=blbabb32#%$@$#%$^$#^"
set "DJANGO_SETTINGS_MODULE=producthunt.settings.local"

set "DBNAME=dbname"
set "DBUSER=dbuser"
set "DBPASS=password"


set "MAILCHIMP_API=--hidden--"
set "MAILCHIMP_LIST_ID=--hidden--"
```

2. In `settings.py`
