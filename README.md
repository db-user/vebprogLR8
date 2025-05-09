# FastAPI Project

Цей проект є базовим додатком на базі FastAPI, який включає наступні можливості:
- CRUD операції для товарів та категорій
- Аутентифікація з використанням JWT
- Використання SQLAlchemy для роботи з базою даних

## Встановлення

1. Клонувати репозиторій:
    ```bash
    git clone https://github.com/db-user/vebprogLR8.git
    ```

2. Встановити залежності:
    ```bash
    pip install -r requirements.txt
    ```

3. Налаштувати файл `.env` для підключення до вашої бази даних.

4. Запустити сервер:
    ```bash
    uvicorn app.main:app --reload
    ```

## Точки доступу

- `/items/` - список всіх товарів
- `/categories/` - список всіх категорій
- `/auth/register` - реєстрація нового користувача
- `/auth/login` - вхід користувача та отримання JWT токена
