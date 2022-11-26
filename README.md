# Проект API для yatube

### **Стек**
![python version](https://img.shields.io/badge/Python-3.7-green)
![django version](https://img.shields.io/badge/Django-2.2-green)
![pytest version](https://img.shields.io/badge/pytest-4.4-green)
![PyJWT version](https://img.shields.io/badge/PyJWT-2.1-green)
![DRF version](https://img.shields.io/badge/DRF-3.12-green)

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
### Запуск проекта:

* Клонируйте репозиторий и перейдите в него в командной строке:

```
git clone https://github.com/TsekovDavid/api_final_yatube.git
```

```
cd api_final_yatube
```

* Cоздайте и активируйте виртуальное окружение:

```
python3 -m venv venv
```
для windows
```
source venv/bin/activate
```
для macos
```
. venv/bin/activate
```

* Установите зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip3 install -r requirements.txt
```

* Выполните миграции из директории с файлом manage.py:

```
python3 manage.py migrate
```

* Запустите проект:

```
python3 manage.py runserver
```
