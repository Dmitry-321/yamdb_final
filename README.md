## Проект «yamdb_final»

### Описание
Проект YaMDb собирает отзывы пользователей на произведения. Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку.

### Технологии
Python 3.8, Django 2.2, DRF, JWT

<details>
<summary><h3>Как запустить проект</h3></summary>

- Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Dmitry-321/yamdb_final
```

```
cd yamdb_final
```

- Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
```

```
source env/bin/activate
```

- Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

- Выполнить миграции:
```
python3 manage.py migrate
```

- Запустить проект:
```
python3 manage.py runserver
```
</details>

### Примеры запросов к API
Примеры запросов доступны в документации по адресу http://127.0.0.1:8000/redoc/ после запуска проекта.

### yamdb_final
![yamdb_workflow](https://github.com/Dmitry-321/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)

