**Постановка задачи:**

*Написать программу, которая из имеющегося массива строк формирует новый массив*
*из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив* 
*можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.* 
*При решении не рекомендуется пользоваться коллекциями,* 
*лучше обойтись исключительно массивами.*

**Решение задачи:**

* исходный строковый массив задается в тексте программы;
* задаем переменную - результирующий строковый массив, устанавливаем для него размер такой же как у исходного массива;
* задаем переменную rescount - количество элементов исходного массива, соответствующих условию задачи, устанавливаем значение переменной 0;
* используем  цикл для поочередной проверки всех строк исходного массива, если длина очередной строки меньше или равна 3, то добавляем эту строку в новый массив под номером rescount, после этого увеличиваем на 1 значение переменной rescount.
* выводим на экран результирующий массив при помощи цикла.

**Блоксхема:**

![Блоксхема!](block.JPG)