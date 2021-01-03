# Quiz School

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-2.0-brightgreen.svg)](https://djangoproject.com)

This is an Quiz app which created with Django Web Freamwork. This app is has two account type, Teacher and Student. Teachers can create new quiz and questions. These quizes automatically drops to students main page. and after solve. Points will send to teacher

![Quiz Django Screenshot](https://simpleisbetterthancomplex.com/media/2018/01/teacher-quiz.png)
 

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/sibtc/django-multiple-user-types-example.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8008**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).
