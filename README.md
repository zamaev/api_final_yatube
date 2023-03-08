# API_YATUBE 
API_YATUBE - CRUD операции для Yatube.

## Требования
- Python (3.7+)

### Пакеты:
- Django (3.2)
- djangorestframework (3.12.4)
- Pillow (9.3.0)

## Установка
Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone git@github.com:zamaev/api_final_yatube.git
cd api_yatube
```
Установить и активировать виртуальное окружение:
```bash
python3 -m venv venv
source venv/bin/activate
```
Установить зависимости из файла requirements.txt:
```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
Выполнить миграции:
```bash
python3 manage.py migrate
```
Запустить проект:
```bash
python3 manage.py runserver
```

## Авторы
- [Айдрус](https://github.com/zamaev)