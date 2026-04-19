# Electronics Shop

Интернет-магазин электроники на Django.

## Возможности
- Каталог товаров с категориями
- Корзина покупок
- Регистрация и вход пользователей
- Админ-панель для управления товарами

## Запуск
```bash
git clone https://github.com/MIOracle01/electronics-shop.git
cd electronics-shop
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
