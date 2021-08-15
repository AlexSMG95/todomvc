**Задание:**
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
- В терминале перейти в каталог проекта
- Выполнить mvn -Dtest=SmokeTest test


**Просмотр отчета allure:**
- Для просмотра отчета allure необходимо установить allure server
- Инструкция (https://docs.qameta.io/allure/)
- В терминале перейти в каталог проекта.
- Выполнить mvn -Dtest=SmokeTest test allure:report
- Открыть в браузере файл /ProjectDirectory/target/site/allure-maven-plugin/index.html

**Оценка покрытия:**
- требования к данному приложению отсутствуют, следует полагаться на пользовательский опыт, исходя из этого можно сделать вывод что тестовое покрытие близится к 100%

**Просмотр отчета allure после выполнения gitlab CI/CD:**

- https://alexsmg95.gitlab.io/-/todomvc/-/jobs/ID/artifacts/target/site/allure-maven-plugin/index.html
- Заменить в ссылке **ID** на последний выполненный ID jobs в разделе CI/CD->Jobs исключая # из ID




