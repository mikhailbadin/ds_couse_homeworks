# Задание к занятию «Продвинутые типы данныx»

## Задание 1

Напишите функцию date_range, которая возвращает список дней между датами `start_date` и `end_date`. Даты должны вводиться в формате `YYYY-MM-DD`.

## Задание 2

Дополните функцию из первого задания проверкой на корректность дат. В случае неверного формата или если start_date > end_date должен возвращаться пустой список.

## Задание 3

Дан поток дат в формате YYYY-MM-DD, в которых встречаются некорректные значения:
`stream = ['2018-04-02', '2018-02-29', '2018-19-02']`
Напишите функцию, которая проверяет эти даты на корректность. Т. е. для каждой даты возвращает True (дата корректна) или False (некорректная дата).

## Задание 4

Напишите функцию, которая возвращает список дат с 1 по вчерашний день текущего месяца. Если дан 1 день месяца, то возвращается список дней прошлого месяца.

## Задание 5

Напишите функцию, которая возвращает точную дату в формате `YYYY-MM-DD` по фразе:

1. `'today'` - сегодняшнюю дату
2. `'last monday'` - прошлый понедельник
3. `'last day'` - Последний день текущего месяца

## Задание 6

Напишите функцию, которая разбивает на недели с понедельника по воскресенье интервал дат между `start_date` и `end_date`. Считайте, что входные данные всегда корректны. В ответ должны входить только полные недели.
