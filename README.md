# E-commerce

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/josuelfeitosa/e-commerce/blob/main/LICENCE)

> Status: Developing ⚠️

### This repository contains an E-commerce web system.

# Technologies used
## Back end
- Python
- Django
## Front end
- HTML / CSS / JS
- Vue
## Deployment in production
- Database: sqlite3
- Docker

# How to run the project

```bash
# Clone repository
git clone https://github.com/josuelfeitosa/e-commerce
# Tools
VSCode and the Dev Container extension.
# Comandos
CTRL+SHIFT+P in VSCode and select the option: 'Open Folder In Container'.
VSCode will reload, lift the container and install the Python extension.
Then open the VSCode terminal and type the following commands:

python manage.py migrate
python manage.py loaddata app/fixtures/initial_data
python manage.py runserver 0.0.0.0:8000
```
Url: [http://localhost:8000](http://localhost:8000)

Login user:

```bash
username: admin
password: 123456
```

# Author

Josuel Feitosa Rodrigues

[Linkedin](https://www.linkedin.com/in/josuel-feitosa-rodrigues/)
