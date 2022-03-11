0. Необходимо распаковать архив promos.zip
1. Переходим в папку с проектом `cd promos`
2. Устанавливаем виртуальное окружение `python -m venv env`
3. Запускаем виртуальное окружение `source env/Scripts/activate`
4. Обновляем pip `python -m pip install --upgrade pip`
5. Устанавливаем в виртуальном окружении зависимости для проекта `python -m pip install --no-cache-dir -r requirements.txt`
6. Делаем миграции для создания базы данных `python manage.py makemigrations && python manage.py migrate`
9. Запускаем локальный сервер `python manage.py runserver`
