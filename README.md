# AV_PyDjango
# AUTOSERVICE

Django проект для автосервиса (просто учусь).

## Установка и запуск

1. Клонируйте репозиторий:

git clone <url-репозитория>
cd autoservice

2. Создайте виртуальное окружение:

bash
python -m venv venv

3. Активируйте виртуальное окружение:

Windows: venv\Scripts\activate
Linux/Mac: source venv/bin/activate

4. Установите зависимости:

pip install -r requirements.txt

5. Создайте файл .env (пример .env.example)

6. Выполните миграции
python manage.py migrate

7. Создайте юзера
python manage.py createsuperuser

8. Запустите сервер
python manage.py runserver

9. Откройте браузер: http://127.0.0.1:8000

http://127.0.0.1:8000/admin - админка с вашим созданным юзером (см. пункт 7).



