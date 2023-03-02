# 28.1

Тестирование нового интерфейса авторизации в личном кабинете от заказчика "Ростелеком Информационные технологии."

Install all requirements: pip3 install -r requirements.txt

Download Selenium WebDriver from https://chromedriver.chromium.org/downloads (choose version which is compatible with your browser)

Run tests: python3 -m pytest -v --driver Chrome --driver-path ~/chrome tests/ -s

WebDriver должен быть расположен в корневой папке каталога.

Команды для запуска файлов с тестами:

python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test_auth_page.py

python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test_auth_by_code.py
