### Что посмотреть?

Проект, который помогает выбрать фильм, выдавая случайное мнение о фильме и ссылку на его описание.

## Технологический стек

* Flask
* Flask-WTF
* Flask-SQLAlchemy
* Flask-Migrate

## Установка

Клонируйте репозиторий и перейдите в него в командной строке, чтобы установить зависимости из файла requirements.txt:

```
git clone 
cd what_to_watch
pip install -r requirements.txt
```

## Запуск

Команда для запуска проекта:

```
flask run
```

Перед запуском наполните `.env` для работы по следующему шаблону:

```
FLASK_APP=opinions_app
FLASK_ENV=development
DATABASE_URI=sqlite:///db.sqlite3
SECRET_KEY=your_secret_key
```

## Авторы:
- [Vakauskas Vitas](https://github.com/Qerced)
