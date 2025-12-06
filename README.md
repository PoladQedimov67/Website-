# Ecommerce Project (Django)

This is a minimal Django project scaffold prepared for the user.  
It includes a `shop` app with a static front-end (HTML + CSS) and placeholder assets.

## How to run locally

1. Create a virtual environment and install requirements:
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

2. Run migrations and start the server:
```bash
python manage.py migrate
python manage.py runserver
```

3. Open http://127.0.0.1:8000 in your browser.

## Notes
- `settings.py` is configured for development (DEBUG=True). Replace SECRET_KEY for production.
- Static files are inside `shop/static/shop/`.
