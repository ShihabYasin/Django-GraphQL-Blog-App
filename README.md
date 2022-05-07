

# Simple Blogging Django Web App (Using GraphQL & Bootstrap)



## Installation:
Pre-requisites:
Install ` Python 3 `, ` pip ` and ` virtualenv `

1. Create a project folder
   
    ```bash
        $ mkdir project
        $ cd project
    ```
2. Create a python 3 virtualenv, and activate the environment to install requirements.
    ```bash
        $ python3 -m venv env
        $ source env/bin/activate
    ``` 
3. Install the project dependencies from `requirements.txt`
    ```
        (env)$ pip install -r requirements.txt
    ```
4. Clone the repository
   
    ```bash
        (env)$ git clone https://github.com/akhil-s-kumar/django-blog-app.git
        (env)$ cd django-blog-app
    ```



## Run Instructions:

Activate virtual environment `env`. Give following commands:

```bash
(env)$ python manage.py makemigrations
(env)$ python manage.py makemigrations blogApp
(env)$ python manage.py makemigrations users
(env)$ python manage.py migrate
(env)$ python manage.py createsuperuser
(env)$ python manage.py runserver
```

## Major Features:

1. Blog List View
2. Recent Posts
3. Category list
4. Search
5. Pagination
6. Blog Detail View
7. Login/Register
8. Comment
9. Create Blog Post
10. Edit Profile
