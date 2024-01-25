#  Personal-Portfolio

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Introduction
Welcome to my personal portfolio and blog site! This project showcases my work, skills, and thoughts through a user-friendly website. Feel free to explore the various sections, including my blog, projects, and more.
![home](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/ea256e5c-2abb-46be-b10e-6ed530e65dc7)

## Table of Content
  * [Introduction](#introduction)
  * [Installation](#installation)
  * [Technologies Used](#technologies-used)
  * [Features](#features)
  * [Website Screenshots](#website-screenshots)
  * [Admin Screenshots](#admin-screenshots)
  
## Installation
1. Clone the repository:
```
git clone https://github.com/Raaxxy/Personal-Portfolio.git
```
2. Navigate to the project directory:
```
cd `Personal-Portfolio`
```
3. Create and activate a new virtual environment:
```
python -m venv env
source env/bin/activate
```
4. Install the project dependencies:
```
pip install -r requirements.txt
```
5. Install the `django-tailwind` module:
```
pip install django-tailwind
```
6. Add `tailwind` to your `INSTALLED_APPS` list in `settings.py`:
```python
INSTALLED_APPS = [
    # ...
    'tailwind',
    # ...
]
```
7. Run the Tailwind CSS configuration command:
```python
python manage.py tailwind init
```
8. Create the database tables:
```python
python manage.py migrate
```
9. Run the development server:
```python
python manage.py runserver
```

## Technologies used
1. Django
2. Python
3. JavaScript
4. HTML
5. CSS
6. Tailwind CSS
7. PostgreSQL

### Primary Modules used
1. Django==4.2.9
2. django-tailwind==3.6.0
3. boto3==1.34.25
4. psycopg2-binary==2.9.9
5. django-tinymce==3.6.1

## Features
1. Responsive design using Tailwind CSS
2. Admin dashboard for managing blog posts and portfolio items
3. Contact form for sending messages to the site owner via SMTP
r
## Pages
- `Home`: Begin your journey on the website's main page, featuring a concise introduction and easy navigation to other sections..
- `About`: Explore details about the site owner, their background, and skills, providing a deeper understanding of the person behind the site.
- `Contact`: Connect with the site owner through a dedicated page housing a convenient contact form for visitors to send messages.
- `Blog`: Dive into a collection of blog posts neatly arranged in reverse chronological order, each post accompanied by links leading to individual pages.
- `Blog Post`: Immerse yourself in the content of a single blog post, encompassing the title, author, date, and a comprehensive narrative.
- `Projects`: Browse through an array of portfolio projects showcased on a dedicated page, each project featuring links redirecting to individual project pages.
- `Categories`: Explore a curated list of blog post categories on a designated page, with convenient links facilitating access to filtered lists of posts for each category.
- `Custom 404 Pages`: Encounter personalized error pages that gracefully appear when users navigate to non-existent pages or encounter errors, ensuring a seamless browsing experience.

## Website Screenshots
![about me](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/28c1aa39-9a8b-489e-975f-d8bfc4474e2b)


![contact](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/450537a1-bd52-4e2c-b341-035b2f3b2c44)


![blog](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/4c389409-2329-4bf9-af26-5591e1ca33ce)


![projects](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/2392218d-6240-42a4-98bf-a1358de64e24)


## Admin Screenshots
![admin dashboard](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/711124a0-8e56-4fc0-bef2-5f17f9538c9c)


![admin blog edit](https://github.com/Raaxxy/Personal-Portfolio/assets/90283239/77a848c4-5dc8-4029-a697-88aeb5cab002)

