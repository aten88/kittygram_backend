# Бэкенд для учебного проекта Kittygram
## Данный проект создан для того чтобы: 
- настроить взаимодействие фронтенда и бэкенда.
- расширить функционал проекта Kittygram.
- подключить интерфейс API.
### Стек проекта: Python3.9, Django 3.2.3, djoser 2.1.0, Pillow 9.0.0, PyJWT 2.6.0, requests 2.29.0
## Описание проекта:
Kittygram учебный проект аналог Instagram в нем владельцы могут постить фото, статьи и комментарии о своих питомцах. А также могут иметь подписчиков и подписываться на страницы других пользователей. В проекте реализованы механизмы: регистрации, авторизации и аутентификации. Реализован интерфейс API приложение может отправлять и получать данные в формате JSON.
### Как запустить проект:
#### Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

#### Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

#### Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

##### Выполнить миграции:

```
python3 manage.py migrate
```

#### Запустить проект:

```
python3 manage.py runserver
```
## Автор: Алексей Тен
