Задание: Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Шаг 1 - инициализируем массив строк array с заданными символами по примеру.
Создаем второй пустой массив строк new_array, куда будем потом помещать строки из первого массива.

Шаг 2 - инициализуем 2 переменные: i и j в качестве счетчика. Переменная i будет использоваться для прохождения по первому массиву строк. Переменная j - для заполнения нового массива. 

Шаг 3 - используем цикл for, чтобы перебрать все элементы первого массива.

Шаг 4 - на каждой итерации цикла проверяем условие - длина текущей строки меньше либо  равна 3?

Шаг 5 - если условие выполняется, то переходим к следующему шагу и заполняем новый массив с индексом j текущей строкой первого массива array[i]. Далее увеличиваем счетчик j и переходим к следующей итерации цикла.
Если условие не выполняется, то сразу переходим к следующей итерации цикла.

Шаг 6 - когда пройдем весь массив, на выходе из цикла for выводим новый массив new_array из строк первого массива, которые меньше либо равны 3 символам.
