
# Flask Web Service for Recruto Test Task

Этот репозиторий содержит код веб-сервиса на Flask, который был разработан в рамках тестового задания для Recruto.

## Описание

Сервис выводит сообщение "Hello Recruto! Давай дружить!", где текст "Recruto" и "Давай дружить" подставляется из GET-параметров запроса.

## Как использовать

1. Перейдите по URL сервиса:
```
https://0135-147-45-116-36.ngrok-free.app
```


2. Добавьте параметры `name` и `message` в URL:
```
https://0135-147-45-116-36.ngrok-free.app/?name=Recruto&message=Давай дружить
```

3. Вы увидите результат:
```
Hello Recruto! Давай дружить!
```

## Локальный запуск

1. Клонируйте репозиторий:
```bash
git clone https://github.com/crowyy03/deepra_test.git
```
2. Перейдите в папку проекта:
```bash
cd deepra_test
```
3. Установите зависимости:
```bash
pip install flask
```
4. Запустите сервер:
```bash
python app.py
```

5. Откройте браузер и перейдите по адресу:
```
http://127.0.0.1:5000/?name=Recruto&message=Давай дружить
```

## Технологии
1. Python 3
2. Flask
