# Домашнее задание

## Реализовать один из класических структур данных данных
Написать реализацию одной из структур данных (очередь, стек, связанный список) и обеспечить функционал работы с этой структурой данных характерной для нее в ввиде функций.
Ну кто хочет поробовать, то можно написать простенькую реализацию хеш функции.

## Reverse or rotate
Входом есть строка `str` чисел. Разбить строку на куски (кусок есть подстрока начальной строки) размером `sz` (проигнорировать последний кусок если размер меньше чем `sz`).

Если кусок представляет собой целое число, такое как сумма кубов его цифр деленная на 2, то reverse этот кусок, иначе поверните его влево на одну позицию.

Условия
если `sz <= 0` или `str ` пустой то возращать надо пусто
если `sz` больше чем длина `str` то это не возможно взять кусок размером  `sz`, то вернуть ""
Примеры
```
revrot("123456987654", 6) --> "234561876549"
revrot("123456987653", 6) --> "234561356789"
revrot("66443875", 4) --> "44668753"
revrot("66443875", 8) --> "64438756"
revrot("664438769", 8) --> "67834466"
revrot("123456779", 8) --> "23456771"
revrot("", 8) --> ""
revrot("123456779", 0) --> ""
revrot("563000655734469485", 4) --> "0365065073456944"
```