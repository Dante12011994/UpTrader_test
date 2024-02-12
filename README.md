# Проект в рамках тестового задания для UpTrader. 
# Выполнил: Гордеев А.В.

## Настройка, установка и запуск

Чтобы запустить приложение на локальном компьютере, вам потребуется Python 3+, установленный на вашем компьютере. 
Выполните все шаги, чтобы запустить этот проект.

1.  Создайте виртуальное окружение, либо запустите проект с Poetry :
```bash
virtualenv env_name
```
    
2.  Активируйте виртуальное окружение:
```bash
On Linux - source virtualenv_name/bin/activate
On Windows - virtualenv_name/Scripts/activate
```

3. Сначала вам нужно клонировать или скачать мой проект из репозитория github:
```bash
git clone https://github.com/Dante12011994/UpTrader_test
```

4. Установите файл зависимостей
```bash
  pip install -r requirements.txt
``` 

5. Запустите сервер!
```python
  python manage.py runserver
```

6. Затем перейдите по адресу ```http://127.0.0.1:8000``` в своем браузере.
