## Описание
Выводит информацию
## Как запустить
1. Запустить командную строку
2. Перейти в директорию
3. Ввести нужную вам команду
## Содержание
* Readme.md
*Pitonysha.py
*confug.json
*Kevin_Levrone.jpg
## Функции XD.py
* read_config
* write_config
* update_config
* main

read_config(filepath):
- Выводит содержимое конфигурации

write_config(filepath, config):
- Записывает словарь config в JSON файл по указанному пути filepath.
- Форматирует JSON для читаемости.

update_config(config, param, value):
- Изменяет значение параметра в словаре config 

main():
- Выполняет действие read или write в зависимости от аргументов.
- Меняет зачение c False на True

## Используемые модули
- argparse
- json

## Автор
barebuhzahida