# Web-приложение ToDo на Django 4

[![Python Version](https://img.shields.io/badge/python-3.11-brightgreen.svg)](https://python.org)

Простой ToDo менеджер, реализованный на веб-фреймворке Django 4

В качестве веб-интерфейса использован фреймворк Bootstrap https://getbootstrap.com/

![ToDo на Django](/todo_img.png)

Клонируем репо

```bash
git clone https://github.com/ajax3101/todo_project.git
```

Устанавливаем и активируем виртуальное окружение

```bash
    python3 -m venv venv
    . venv/bin/activate
 ```

Устанавливаем модули

```bash
    pip install Django 
```

Или загружаем файл с зависимостями проекта

```bash
 pip install -r requirements.txt
```

Запус приложения

```bash
 python manage.py makemigrations 
 python manage.py migrate
 python manage.py runserver 
```
