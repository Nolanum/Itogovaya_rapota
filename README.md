Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Описание алгоритма решения:

Сначало вводится необходимое колличество элементов массива, затем создается массив размером с указанное количество элиментов. Затем вводятся непосредственно сами элементы массива, ктороые циклом вводятся в сам массив. 
При проверке условия (<=3) сначала идёт цикл, внутри которого считается количество таковых элементов. Затем создаётся результативный массив с посчитанной данным циклом размерностью. После этого идёт цикл, который повторно проверяет условие (<=3), но в результате не считает элемент, а добавляет его в новый массив с результатом. И после каждого такого добавления к переменной J добавляется 1, чтобы следующий элемент добавлялся к следующему.

Блок-схема илюстрирующая программу "Снимок экрана 2022-09-21 в 12.41.56.png".

Код программы в файле Zadacha
