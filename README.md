## О проекте ACME

Данный проект позволяет делать записи о днях рождениях Ваших друзей и близких. Также возможен расчет количества оставшихся дней до дня рождения. Не беспокойтесь. что Ваши данные может посмотреть другой пользователь, на странице предполагается авторизация и конфиндециальность записей!

### Как запустить проект:

Cоздать и активировать виртуальное окружение:

Windows
```
python -m venv venv
source venv/Scripts/activate
```
Linux/macOS
```
python3 -m venv venv
source venv/bin/activate
```

Обновить PIP

Windows
```
python -m pip install --upgrade pip
```
Linux/macOS
```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

Windows
```
python manage.py makemigrations
python manage.py migrate
```

Linux/macOS
```
python3 manage.py makemigrations
python3 manage.py migrate
```

Запустить проект:

Windows
```
python manage.py runserver
```

Linux/macOS
```
python3 manage.py runserver
```