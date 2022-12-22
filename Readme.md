# To_Do_List [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

## A Basic To-Do Web Application using Django Framework

### Features

- User Authentication - Users can register, login and logout
- Add, Edit, Mark tasks as Complete/Incomplete and Delete Tasks

### Steps to be followed for first time use

- Create an Environment variable `DJANGO_ENV=DEV` to run the app in local.

  ```
  venv\Scripts\activate.bat
  ```

- Run the below command - This will create the tables
  ```
  python manage.py migrate
  ```
- Create an `admin` user by running these following command

  ```
  $ python manage.py createsuperuser

  $ python manage.py runserver
  ```
![Screenshot 2022-12-22 130118](https://user-images.githubusercontent.com/73239204/209089160-624c06bc-448d-4f20-8a0d-9544bf004bf6.jpg)
![Screenshot 2022-12-22 130252](https://user-images.githubusercontent.com/73239204/209089164-02befe58-ac90-4fb7-8b27-c0042bc28186.jpg)
