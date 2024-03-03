# Домашнее задание к занятию "`Базы данных`" - `Пешкин Евгений`


### Задание 1.

Опишите не менее семи таблиц, из которых состоит база данных:
    • какие данные хранятся в этих таблицах;

#### Ответ:
    1) ФИО сотрудника: Данные о полном имени сотрудника
    2) Оклад: Информация о заработной плате сотрудника
    3) Должность: Информация о должности, которую занимает сотрудник.
    4) Тип подразделения - это тип иерархической структуры в которой работает конкрентой сотрудник
    5) Структурное подразделение:  Конкретное название подразделения, например, "Отдел разработки" или "Отдел маркетинга".
    6) Дата найма: Дата, когда сотрудник был нанят наработу
    7) Адрес Филиала: Адрес офиса или филиала, к которому привязан сотрудник
    8) Проект на который назначен: Название проекта, в который сотрудник был назначен

    • какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.

#### Ответ:
    1) ФИО сотрудника:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).
    2) Оклад:
Тип данных в PostgreSQL: NUMERIC или MONEY (числовой тип данных для хранения денежных значений).
    3) Должность:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).
    4) Тип подразделения:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).
    5) Структурное подразделение:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).
    6) Дата найма:
Тип данных в PostgreSQL: DATE (тип данных для хранения даты без времени).
    7) Адрес Филиала:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).
    8) Проект на который назначен:
Тип данных в PostgreSQL: VARCHAR (строковый тип данных для хранения символов переменной длины).



### Задание 1.2.

Привидте решение к следующем виду:

Сотрудник (

1) идентификатор, первичный ключ, serial
2) фамилия varchar(50),
3) ...
4) идентификатор структурного подразделения, внешний ключ, integer).

#### Ответ:
[Решение_в_формате_EXCEL](https://github.com/SoReX48/12-01.md/blob/main/Базы_данных/hw-12-1_homework.xlsx)


