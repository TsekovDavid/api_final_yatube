# Проект API для yatube
### С помощью этого проекта можно:
* Подписываться на авторов и смотреть подписки.
* Просматривать, создавать новые, удалять и изменять посты.
* Просматривать группы.
* Комментировать, смотреть, удалять и обновлять комментарии.
* Фильтровать по полям.

#### Документация по адресу:
```
http://localhost:8000/redoc/
```
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/api_final_yatube.git
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
