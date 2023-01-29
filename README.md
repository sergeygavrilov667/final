
"# final" Финальный проект Тестировщик - автоматизатор на PYTHON

Тестирование формы авторизации Личного кабинета Ростелеком https://b2c.passport.rt.ru

Ссылка на требования по проекту -https://docs.google.com/document/d/1gfqiNEX5YYZBXeBQCnAccXyHeYH-COMx/edit?usp=sharing&ouid=111093610372337896591&rtpof=true&sd=true

По заданию тестирования необходимо:

Протестировать требования.

Разработать тест-кейсы (не менее 15).

Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.

Оформить описание обнаруженных дефектов ( составить баг-репорты). Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов).

Ссылка на тестирование требований, тест-кейсы, баг-репорты:https://docs.google.com/spreadsheets/d/1UsoJv-77-ZBpfKKrhkWFDfFhthFX3nlRudpIuDn-p18/edit?usp=sharing

base_data.py - базовые классы, процедуры, функции и локаторы для автотестов

settings.py - регистрационные данные для позитивных тестов авторизации

test_authorization_RT - набор автотестов, нумерация соответствует номеру тест-кейса

запуск автотестов (драйвер в одной папке с тест-скриптом)

Запуск тестов:

Установить все внешние зависимости командой pip install -r requirements.txt

Скачать версию Selenium WebDriver для Chrome 108 версии

Запустить тесты можно прописав команду:

python -m pytest -v --driver Chrome --driver-path <Путь до вебдрайвера>\chromedriver.exe test_authorization_RT.py
