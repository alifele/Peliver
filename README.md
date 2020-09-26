# Peliver


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
