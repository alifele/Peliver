# Peliver

[![Python Version](https://img.shields.io/badge/python-3.7-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-2.1-brightgreen.svg)](https://djangoproject.com)
[![Django Version](https://img.shields.io/badge/Open-Source-blue.svg)](#)

![Peliver](https://github.com/alifele/Peliver/raw/master/pics/logo.png  "Peliver")
## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/alifele/Peliver.git
```

Make a virtual environment
```python
python3 -m venv WebDev
```

activate your virtual environment
```bash
source WebDev/bin/activate

```

Install the requirements:

```bash
pip install -r requirements.txt
```

Apply the migrations:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-upload-example/blob/master/LICENSE).
