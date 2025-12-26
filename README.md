# Лабораторная работа №1 по теме "Docker: создание и управление контейнерами"

1. Цель работы
Целью работы является изучение работы с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.

## Ход работы

Клонировали репозиторий данный преподавателем. Создали и заполнили файл Dockerfile image
<img width="1557" height="672" alt="image" src="https://github.com/user-attachments/assets/a078553f-4082-4971-9a8b-0d2454a2fbd3" />

Запустили докер контейнер на порте 1234 
<img width="1236" height="593" alt="image" src="https://github.com/user-attachments/assets/e5174787-164f-48c3-a7c3-523d3e6b648e" />
<img width="1919" height="792" alt="image" src="https://github.com/user-attachments/assets/f13d28be-776e-4e35-9746-264023d6407b" />


Написали docker-compose.yml для развертывания этого приложения вместе с базой данных PostgreSQL, предусмотреkb проброс порта 1234, а также возможность расширения или подключения сторонних сервисов при необходимости.

<img width="393" height="578" alt="image" src="https://github.com/user-attachments/assets/5b384240-9bfd-45f1-970c-7a72fecba522" />

Запустиkb стек через docker-compose и убедиkbcm что подключение к базе данных произошло успешно.
<img width="293" height="88" alt="image" src="https://github.com/user-attachments/assets/2acb83fc-8941-41b3-b50e-5cd8c3c221fd" />
