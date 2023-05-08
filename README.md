# QA-java-diplom-2
## О проекте
Автотесты API для проверки учебного сервиса [Stellar Burgers](https://stellarburgers.nomoreparties.site/)
Эндпоинты описаны в [Документации API](https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/api-documentation.pdf)
### Цели:
- Протестировать необходимые эндпоинты (проверить тело и статус код ответа)
- Обеспечить независимость тестов
- Сформировать отчёт Allure

## Используемые инструменты
- Java 11
- maven 4.0.0
- JUnit 4.13.2
- rest-assured 5.3.0
- allure 2.15.0
- maven-surefire-plugin 2.22.2

- javafaker 1.0.2


- gson 2.10.1


## Запуск тестов и построение отчёта:
- mvn clean test
- mvn allure:serve