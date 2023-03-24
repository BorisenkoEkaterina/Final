
# "Итоги блока. Выбор специализации"

### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна трём символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры результатов работы программы
["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []/*

Решение:
1. Задаём массив вручную: [ "hello", "2", "world", ":-)", "1234", "1567", "Rus", "-2", "computer science", "Russia", "Denmark", "Kazan", "GB", "GBU" ]).

2. Используем метод:  TestArray - он вычисляет количество строк,, длина которых не превышает 3 символа;
3. Создаём переменную count = 0. Далее присваеваем ей значение,равное количеству строк, длина которых 3 символа и меньше.
4. В цикле проверяем условие (строка <3). Если да,  то count ++, i ++
   Если count > 3 , то i++.
5. Далее методом FillArray - создаем массив, состоящий из строк, длина которых меньше 3х символов.
6. Вызываем  метод PrintArray для вывода результата.
