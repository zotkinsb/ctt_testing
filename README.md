# Project Name

Документация по сервису


## Для запуска

1) Установите docker
2) Запустите make - файл командой make start

## Линтер

Используется `wemake-python-styleguide`.

Для тестов отключена проверка наличия документации модуля и описания аргументов в Docstring. 

Конфигурация находится в `setup.cfg`

Запуск: `flake8`

## Тестирование

Запуск: `pytest .`

## CI-CD

В GitHub actions настроен запуск линтера и тестов при событии push.

