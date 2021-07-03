# ExamTasks - Решенные примеры задач на экзамен по КПЯП

> Решенные номера: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 16, 17, 18, 19, 20, 15, 18, 21, 22, 23, 26, 27, 28, 29

> Номера, которые нужно решить: 25

> Номера 30 - 33 копипаста других задач

> Номер 24 нерешаем из-за своего условия (просто вдумайтесь в это)

## Список задач:

1.	Составьте функцию-шаблон для нахождения максимального элемента главной диагонали квадратной матрицы А (nхn). В главной функции оформите вызов шаблона для различных типов данных.

2.	Составьте и оформите в виде отдельной функции сортировку по убыванию одномерного динамического массива Mas из n элементов. Размерность массива и его элементы задаются пользователем.

3.	Создайте функцию, реализующую простейший калькулятор (над двумя числами необходимо производить операции +, -, *,/). Параметры должны передаваться в функцию по ссылке.

4.	Запишите определение класса TRAIN, в котором хранится информация о номере поезда, его времени отправления и пункте назначения. В классе должны быть реализованы три конструктора, а также методы, позволяющие присваивать значения полям класса и выводить их на экран.

5.	Разработайте в виде отдельной функции поиск количества слов, начинающихся и заканчивающихся на, одну и ту же букву в строке Str. Слова в строке разделены одним пробелом. В функции main() оформить вызов функции для строки, введенной с клавиатуры.

6.	Разработайте подпрограмму на языке C#, вычисляющую сумму или произведение цифр натурального числа (выбор осуществляется пользователем). В функции main() оформить вызов функции для числа, введенного с клавиатуры.

7.	Разработайте функцию-шаблон для нахождения количества строк двумерного массива Mas(nxm), сумма элементов которых меньше заданного числа k. В главной функции оформите вызов шаблона для различных типов данных.

8.	Реализуйте программу в консоли C#, которая позволяет пользователю суммировать вводимые с клавиатуры числа до тех пор, пока не введена цифра 0. Полученная сумма должна выводиться на экран. Оформить вывод значений с помощью метода Console.WriteLine тремя способами (конкатенация, форматный вывод и интерполяция).

9.	Составить и оформить в виде отдельной функции проверку - одинаковое ли число открывающихся и закрывающихся скобок в строке Str. Слова в строке разделены одним пробелом. В функции main() запишите операторы вызова данной функции для строки Str.

10.	Разработайте функцию-шаблон, выполняющую поиск элементов одномерного массива, стоящих после первого максимального элемента. В функции main() оформите вызов шаблона для массивов с различными типами данных.

11.	Запишите определение класса DISTANCE (на языке C#), в котором хранится информация о длине (метры и сантиметры). В классе должны быть реализованы три конструктора, а также метод, позволяющий присваивать значения, вводимые с клавиатуры, полям класса и метод, который выводит эти значения на экран в виде: 4м 25см.

12.	Разработайте функцию-шаблон для нахождения максимального элемента столбца с заданным номером к прямоугольной матрицы А(n x m). В главной функции main() оформить вызов шаблона для массивов разных типов.

13.	Запишите программу в консоли C#, которая позволяет информацию из одного текстового файла скопировать в другой.

14.	Разработайте функцию-шаблон определяющую минимальную цифру главной диагонали матрицы А(nхn). В функции main() организуйте вызов шаблона для массивов различных типов.

15.	Разработайте функцию, которая в строке, переданной ей в качестве параметра, заменит все двоеточия (:) на точку с запятой (;). Подсчитайте количество замен.

16.	Разработайте класс DATE (на языке C#), в котором хранится информация о дате (число, месяц и год). В классе должны быть реализованы три конструктора, а также метод, позволяющий присваивать значения, вводимые с клавиатуры, полям класса и метод, который выводит эти значения на экран в виде: 05.01.2020 г.

17.	Разработать класс с двумя целочисленными полями. Создать конструктор копирования. Разработать метод, заменяющий поля на их последние цифры. Разработать метод вывода полей. Протестировать все методы.

18.	Разработайте программу на языке C#, которая находит минимальный элемент и его расположение в двумерном массиве. Размер массива вводится с клавиатуры. Продемонстрируйте работу с циклом foreach.

19.	Разработайте класс STUDENT, в котором хранится информация о фамилии учащегося, его адрес и средний балл. В классе должны быть реализованы три конструктора, а также методы, позволяющие присваивать значения полям класса и выводить их на экран.

20.	Определить класс Person.
    * Который имеет поля:
      1. закрытое поле типа string, в котором хранится имя; 
      2.	закрытое поле типа string, в котором хранится фамилия; 
      3.	закрытое поле типа System.DateTime для даты рождения.
    * В классе Person определить конструкторы: 
      1. конструктор c тремя параметрами типа string, string, DateTime для инициализации всех полей класса;  
      2.	конструктор без параметров, инициализирующий все поля класса некоторыми значениями по умолчанию.
    * В классе Person определить свойства c методами get и set: 
      1. свойство типа string для доступа к полю с именем;  
      2. свойство типа string для доступа к полю с фамилией; 
      3. свойство типа DateTime для доступа к полю с датой рождения; 
      4. свойство типа int c методами get и set для получения информации(get) и изменения (set) года рождения в закрытом поле типа DateTime, в котором хранится дата рождения.
    * В классе Person определить:
      1.	перегруженную(override) версию виртуального метода string ToString() для формирования строки со значениями всех полей класса; 
      2.	виртуальный метод string ToShortString(), который возвращает строку, содержащую только имя и фамилию. 
      3. В класс Person добавить реализацию интерфейсов System.IComparable для сравнения объектов типа Person по полю с фамилией; System.Collections.Generic.IComparer(Person) для сравнения объектов типа Person по дате рождения. 

21.	Разработайте функцию для нахождения НОД двух целых чисел а и b, используя алгоритм Евклида (если а делится на b,) то НОД(а, b)=b, в противном случае НОД(а, b)=НОД(b, а mod b). В функции main() оформить вызов функции для заданных чисел.

22.	Разработайте программу на языке С#, выполняющую поиск максимального элемента и его местоположение в одномерном массиве. Значения элементов массива задаются пользователем. Продемонстрируйте работу с циклом forech.

23.	Разработайте программу на языке С#, которая определяет количество отрицательных элементов двумерного массива. Массив заполнить случайными числами. 

24.	Разработайте программу на языке С#, которая для одномерного массива выводит на экран номера всех минимальных элементов. Продемонстрируйте работу с циклом forech.

25.	Разработайте класс Triangle на языке С#, который включает следующие элементы:
  * Поля: int а, b, с;
  * Конструктор, позволяющий создать экземпляр класса с заданными длинами сторон;
  * Методы, позволяющие:
    1.	вывести длины сторон треугольника на экран;
    2.	рассчитать периметр треугольника;
  * Свойства:
    1.	позволяющее получить-установить длины сторон треугольника (доступное для чтения и записи);
    2.	позволяющее установить, существует ли треугольник с данными длинами сторон (доступное только для чтения).

26.	Разработайте программу на языке С#, которая для заданной строки str подсчитывает количество содержащихся в ней цифр.

27.	Разработайте программу на языке С#, которая для заданной строки str удаляет все символы X.

28.	Разработайте программу на языке С#, которая для заданной строки str выводит на экран последовательность символов, расположенных после последнего двоеточия.

29.	Разработайте программу на языке С#, которая для заданной папки определят количество файлов, имя которых начинается с символа а.

30.	Составьте функцию-шаблон для нахождения максимального элемента главной диагонали квадратной матрицы А (nхn). В главной функции оформите вызов шаблона для различных типов данных.

31.	Составьте и оформите в виде отдельной функции сортировку по убыванию одномерного динамического массива Mas из n элементов. Размерность массива и его элементы задаются пользователем.

32.	Создайте функцию, реализующую простейший калькулятор (над двумя числами необходимо производить операции +, -, *,/). Параметры должны передаваться в функцию по ссылке.

33.	Разработайте в виде отдельной функции поиск количества слов, начинающихся и заканчивающихся на, одну и ту же букву в строке Str. Слова в строке разделены одним пробелом. В функции main() оформить вызов функции для строки, введенной с клавиатуры.
