#Autotest_finalproject
##Автоматизация теста к API

## Описание проекта
Данный проект представляет собой автоматизацию теста к API. Сценарий автотеста основан на задании, подготовленном коллегами-тестировщиками.

## Шаги автотеста
1. Выполнить запрос на создание заказа.
2. Сохранить номер трека заказа.
3. Выполнить запрос на получение заказа по треку заказа.
4. Проверить, что код ответа равен 200.

## Файлы проекта
В данном проекте содержатся следующие файлы:

1. **data.py**: Файл с данными, используемыми при выполнении запросов. 
2. **sender_stand_requests.py**: Файл с функциями для создания заказа и получения информаии о заказе по треку номеру
3. **create_order.py**: Файл с автотестом, осуществляющим создание заказа и проверку получения данных о заказе по треку.
4. **configuration.py**: Файл с классом, содержащим методы для выполнения запросов к API.

## Требования для запуска проекта
Для запуска проекта необходимо наличие следующих инструментов и библиотек:

- Python 3.6 и выше
- Библиотеки (установка через pip): requests

## Инструкция по запуску проекта
1. Установите Pytest (если не установлен).
2. Установите необходимые библиотеки, выполнив команду `pip install -r requirements.txt`.
3. Откройте командную строку (терминал) и перейдите в директорию проекта.
4. Запустите автотест, выполнив команду `pytest`.
5. После выполнения автотеста вы увидите результаты проверки.

## Автор
Автор проекта: Феоктистов Павел
Дата создания: 08.09.2023
