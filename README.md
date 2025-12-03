# VIVT-django
Как django_sprint1, только с БД. Данные для БД находятся в файле db.json.
<img width="1640" height="989" alt="image" src="https://github.com/user-attachments/assets/7670f5c3-dce8-4f7b-a0fc-d485475cb1bb" />

## 🚀 Как запустить
```bash
# 1. Клонировать репозиторий
git clone https://github.com/Glockych/django_sprint3.git
cd django_sprint3

# 2. Создать и активировать виртуальное окружение
python -m venv myvenv

# Windows:
.\myvenv\Scripts\activate
# macOS/Linux:
source myvenv/bin/activate

# 3. Установить зависимости
pip install -r requirements.txt

# 4. Перейти в рабочую директорию и применить миграции
cd blogicum 
python manage.py migrate

# 5. Запустить сервер
python manage.py runserver
```
