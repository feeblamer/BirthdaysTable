# Birthdays Table

Консольное приложение с таблицей дней рождений. В данном репозитории находится только описание приложения. 

## Основная идея приложения

Приоложение должно вывыводить таблицу с датами дней рождений. В таблице должны быть имена людей. 


### Декомпозиция

Приложение должно иметь две основных функции:
- Вывод таблицы дат
- Добавление новой даты

### Данные

Для упрощения написания приложения, данные будут храниться в текстовом файле. Будет возможность использовать разыне форматы. 
В первую очередь приложение создается для учебных целей. Поэтому для изучения форматов различных файлов можно применить:
- JSON
- XML
- HTML + CSS
- CSV

В дальнешейм при улучшении приложения можно использовать базы данных, например Sqlite3.

## Приложение
### Вывод таблицы дат

1. Приложение запускается без аргументов командной строки
   1.1. В дальнешем можно добавить позиционный аргумент путь к файлу с данными
3. Открыть файл с данными для чтения
4. Прочитать данные построчно или все сразу
   4.1. Если файл имеет особоенный формат, данные нужно распарсить с помощью библиотек.
   4.2. Потом привести к каомуто виду для дальнейшего форматирования.
6. Отформатировать данные построчно
7. Вывести отформатированные данные в консоль

### Добавление новой даты


