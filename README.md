# Final-control-work-on-the-main-block
Итоговая контрольная работа по основному блоку

1.	Посредством метода Clear, удаляем из буфера Консоли и её окна отображаемую ранее информацию.

2.	Создаём метод NewArray, который принимает в себя два аргумента, а именно два массива строк: array1 и array2.
    В теле данного метода объявляем переменную count, которой присваиваем значения нуля. Оставаясь в теле данного метода, открываем цикл for.
  	В данном цикле объявляем переменную i с типом целого числа и присваиваем ей значение нуля. Ставим условие, в котором указываем, что переменная i, должна быть меньше длинны массива array1.
  	После этого объявляем оператор инкремента. Оставаясь в теле цикла for, объявляем оператор if с условием – пока длина массива меньше или равна трём.
  	Пока данное условие верно, происходит присвоение нового значение, старому элементу массива array2. Далее переменная count увеличивается на единицу.
  	Вышеописанная конструкция в данном методе, позволяет нам из массива строк array1, выбрать те элементы, в которых длина строк составляет три или менее символов. Далее выбранные элементы записываются в новый массив строк array2.

3.	Создаём метод PrintArray, который принимает в себя один аргумент в виде массива строк.
    В теле данного метода открываем цикл for (разница с циклом for описанным выше – это условие: переменная i, которая также является «счётчиком», должна быть меньше длины массива).
    С помощью данного цикла и метода Write, а также форматируемой строки, происходит заполнение и вывод на экран массива строк.

Далее отображается основная часть программного кода, отделённая комментарием в виде:
(// ------------------------------------------------------------------)

4.	Объявляется массив строк array. В данный массив присваивается четыре элемента строчного значения.

5.	Объявляется массив строк newArray. В данный массив присваивается длинна массива array.

6.	Задействуем выше созданный метод NewArray, в качестве аргументов в него входят два объявленных массива строк array и newArray.

7.	Задействуем выше созданный метод PrintArray, в качестве аргумента в него входит объявленный массив строк newArray.
