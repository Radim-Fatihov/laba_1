# Лабораторная работа №1 по теме "Docker: создание и управление контейнерами"

1. Цель работы
Целью работы является изучение работы с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.

## Ход работы

Клонировали репозиторий данный преподавателем. Создали и заполнили файл Dockerfile image
<img width="1254" height="372" alt="image" src="https://github.com/user-attachments/assets/fc8cab73-7fab-47b2-b409-96041fc3bc60" />


Запустили докер контейнер на порте 1234 
<img width="1255" height="524" alt="image" src="https://github.com/user-attachments/assets/78b4c89c-7b1f-4719-bd2c-ab55e237f827" />

Написали docker-compose.yml для развертывания этого приложения вместе с базой данных PostgreSQL, предусмотреkb проброс порта 1234, а также возможность расширения или подключения сторонних сервисов при необходимости.

<img width="393" height="578" alt="image" src="https://github.com/user-attachments/assets/5b384240-9bfd-45f1-970c-7a72fecba522" />

Запустили стек через docker-compose и убедились что подключение к базе данных произошло успешно.
<img width="293" height="88" alt="image" src="https://github.com/user-attachments/assets/2acb83fc-8941-41b3-b50e-5cd8c3c221fd" />
