# LibraryApp1

## Описание

'LibraryApp1' - это веб-приложение для управления книгами и читателями в библиотеке. Позволяет добавлять, удалять и редактировать информацию о книгах и читателях, а также вести учет выданных книг для читателей.

## Технологии

Tomcat Server: Приложение развернуто на сервере приложений Tomcat, который обеспечивает выполнение и поддержку веб-приложения.

PostgreSQL: База данных для хранения информации о книгах, читателях и выданных книгах.

JDBC Template: Используется для взаимодействия с базой данных PostgreSQL.

Spring Framework используется для разработки веб-приложения и управления бизнес-логикой. Базовая архитектура приложения реализована с использованием Spring MVC Framework, который обеспечивает управление бизнес-логикой, обработку HTTP запросов и формирование HTTP ответов в соответствии с паттерном MVC (Model-View-Controller).

## Установка и запуск
Для запуска 'LibraryApp1' выполните следующие шаги:
1. Склонируйте репозиторий.
2. Соберите jar артефакт, используя команду 'mvn package'.
3. Запустите приложение, используя команду 'java -jar target/LibraryApp1.jar'.

## Использование API
- 'GET /people' - получение списка доступных валют.
- 'GET /books' - получение списка доступных валют.

## Лицензия
Этот проект лицензирован под лицензией MIT.