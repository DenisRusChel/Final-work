**Задача:** 

Написать программу, которая из имеющегося массива строк формирует 
новый массив из строк, длина которых меньше, либо равна 3 символам. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения 
алгоритма. 
При решении не рекомендуется пользоваться коллекциями, лучше 
обойтись исключительно массивами.

**Описание решения:**

1. Объявляется два массива: изначальный(массив1) и вторый(массив2) такой же длины. 

2. Затем метод(FinalArray), который принимает в себя 2 массива → в цикле перебираются элементы массива1 и задается проверка условия ( <=3 ): если условие выполняется → элемент первого массива заносится в count элемент  массива2. Переменная count  задана чтобы поочередно закидывать из массива1 в массив2. 

3. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

4. Затем метод PrintArray выводит на экран массив2. 

Скриншот метода FinalArray добавлен в папку Block_diagram

![Блок-схема](Block_diagram\Сhart.png)

Реализация программного кода → Task\Program.cs


