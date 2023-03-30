# Проект Лотерея игрушек
## Задача
Необходимо написать проект, для розыгрыша в магазине игрушек.

## Пояснения
Точка входа в приложение - файл App.java. Имеет команды: ADD, LOTTERY, PRIZES, EXIT. Не важно, вводить их заглавными или строчными.

Реализовала id - как уникальные номера для игрушек. Если в приложении уже есть набор игрушек, каждой будет присвоен новый уникальный номер.

Командой add можно добавить новую поставку игрушек для лоттереи. Я реализовала автоматическую генерацию, чтобы пользователю не приходилось вводить все характеристики игрушек.

Команда lottery случайно выбирает игрушку из предложенного списка и записывает игрушку в файл.

Команда prizes считывает из файла строки с призовыми игрушками, переводит их в экземпляры класса Toy и выводит в консоль.

Exit - выход.