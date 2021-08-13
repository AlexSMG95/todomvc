Задание:
- Используя любой фреймворк автоматизации тестирования.
- Реализовать Smoke проверку данного приложения по ранее подготовленным тестам.
- Сопроводить инструкцией по запуску.
- Оценить покрытие.

**Ранее подготовленные тесты:**
- https://docs.google.com/spreadsheets/d/1wLzER38ey7L5vCc8sB1w09wt5rKWB_Zi0GwJAE5hnqw/edit#gid=0

**Инструкция по запуску:**
- Склонировать проект на ПК.
- Дождаться установки maven расширений и плагинов.
- Установить google chrome.
- Скачать и распаковать ChromDriver (https://chromedriver.storage.googleapis.com/index.html) эдентичный по версии установленного google chrome
- В файле проекта "TestBase" изменить переменную driverPath на путь до распакованного ChromeDriver
- Запустить  SmokeTest


**Просмотр отчета allure:**
- Для просмотра отчета allure необходимо установить allure server
- Инструкция (https://docs.qameta.io/allure/)
- Запустить автотесты и дождаться прогона всех тестов.
- В конмандной строке перейти в каталог проекта
- Выполнить allure serve

Оценка покрытия:
- требования к даннопу приложению отсутствуют, следует полагаться на пользовательский опыт, исходя из этого можно сделать вывод что тестовое покрытие близится к 100%	

