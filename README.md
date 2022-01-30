# API для проекта yatube
## API позволяет работать с постами, комментариями и подписками

### Документация API доступна локально по адресу http://127.0.0.1:8000/redoc


Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/m00nrock/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```