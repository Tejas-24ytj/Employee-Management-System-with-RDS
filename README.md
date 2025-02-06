
# Employee Management System

An Employee Management System in Django keeps track of all of the employee’s information and data. We’ve created all of the employee's and company crud (create, read, update, and delete) operations. This is a role-based module in which the admin can perform any operation on the data.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

## Features

•	Add Employee - The admin can add the employee in this software.

•	View Employee Details - The admin can view the list of all employee details.

•	Update Employee Details - The admin can edit the employee details and information.

•	Delete Employee - The admin can remove the employee from the database.

> This Application was created using Python, Django, HTML/CSS, and Bootstrap.

## Sample video of this Project

Employee Management System -

https://user-images.githubusercontent.com/95544839/215315801-f1f4bbfb-53c2-4e5a-8090-844e4f572b46.mp4

## Installation 

This requires [Python](https://www.python.org/) v3.8+ and [Django](https://www.djangoproject.com/) v4.0.4+ to run.

```bash
  pip install -r requirements.txt
```

### Add your database name (change settings.py file)

```bash
  DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        # 'NAME': BASE_DIR / 'db.sqlite3',
        'NAME': 'newemp', # add you database name (schema name eg: newemp)
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST': 'localhost',
        'PORT': '3306'
    }
  }
```

### Update your database (By Applying migrations)

```bash
python manage.py migrate
```

### Install the dependencies and start the server.

```bash
  python manage.py runserver
```

![Image](https://github.com/user-attachments/assets/5f7675e4-df4d-41ab-ac64-ced5deac06bc)

![Image](https://github.com/user-attachments/assets/bb7fc603-011e-4183-825a-7170e758c784)

![Image](https://github.com/user-attachments/assets/f8a73b5c-04af-4d9a-8892-e8bf5ecfcc8d)

![Image](https://github.com/user-attachments/assets/1ae222e1-ec87-4382-87cf-b6b8604ed591)

