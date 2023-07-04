# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

![alt text](https://github.com/Cryosphere/goit-node.js-hw-01-CLI-app/blob/main/pics/1.png?raw=true)

# Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

# Добавляем контакт и выводим в консоль созданный контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

# Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
