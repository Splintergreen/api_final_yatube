### Проект API для Yatube
```
Возможности социальной сети Yatube теперь доступны и через API
```
### Как запустить проект:
```
Клонировать репозиторий и перейти в него в командной строке:

```
SSH
git clone git@github.com:Splintergreen/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python manage.py runserver

### Документация проекта и примеры запросов
```
Документация доступна по адресу http://127.0.0.1:8000/redoc/
```