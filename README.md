**FinalTask**

**Задача :** *Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами*

**Описание алгоритма решения:** Сначала объявляем два массива: массив выбранный из задания и второй такой же длинны.

Потом используем метод (**CheckArray**) с помощью данного метода цикл выполняет проверку условия задачи (*строк длина которых меньше, либо равна 3 символам*) (**<=3**), если элемент массива проходит проверку условия мы заносим его в переменную (**count**) второго массива.

После присвоения значения переменная (**count**) увеличивается на 1 и возвращается к циклу (**for**) в котором (**i**) увеличивается на 1 и так до конца цикла.

Как только цикл переберет все элементы массива по условию используем метод (**PrintArray**) для вывода нового массива в консоль.