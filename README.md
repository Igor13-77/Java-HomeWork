# Java-HomeWork
Репозиторий для сдачи домашних заданий по курсу Java
HomeWork001 (Домашнее задание по первому семинару)
1. (task1) Вычислить n-ое треугольного число(сумма чисел от 1 до n), n!
2. (task2) Вывести все простые числа от 1 до 1000
3. (task3) Реализовать простой калькулятор
4. (task4) Задано уравнение вида q + w = e, q, w, e >= 0. Некоторые цифры могут быть заменены знаком вопроса, например 1? + ?5 = 69.
Требуется восстановить выражение до верного равенства. Предложить хотя бы одно решение или сообщить, что его нет.

HomeWork002 (Домашнее задание по второму семинару)
1. Дана строка sql-запроса "select * from students where ". Сформируйте часть WHERE этого запроса, используя StringBuilder. Данные для фильтрации приведены ниже в виде json-строки.
Если значение null, то параметр не должен попадать в запрос.
Параметры для фильтрации: {"name":"Ivanov", "country":"Russia", "city":"Moscow", "age":"null"}
2. (task2) Реализуйте алгоритм сортировки пузырьком числового массива, результат после каждой итерации запишите в лог-файл.
3. (task3) В файле содержится строка с данными:
[{"фамилия":"Иванов","оценка":"5","предмет":"Математика"}, {"фамилия":"Петрова","оценка":"4","предмет":"Информатика"}, {"фамилия":"Краснов",### "оценка":"5","предмет":"Физика"}]
Напишите метод, который разберёт её на составные части и, используя StringBuilder создаст массив строк такого вида:
Студент Иванов получил 5 по предмету Математика.
Студент Петрова получил 4 по предмету Информатика.
Студент Краснов получил 5 по предмету Физика.

HomeWork003 (Домашнее задание по третьему семинару)
1. (task1) Реализовать алгоритм сортировки слиянием.
2. (task2) Пусть дан произвольный список целых чисел. Удалить из него чётные числа.
3. (task3) Задан целочисленный список ArrayList. Найти минимальное, максимальное и среднее арифметичское этого списка.

HomeWork004 (Домашнее задание по четвертому семинару)
1. (task1) Пусть дан LinkedList с несколькими элементами. Реализуйте метод, который вернет “перевернутый” список.
2. (task2) Реализуйте очередь с помощью LinkedList со следующими методами:
enqueue() - помещает элемент в конец очереди, dequeue() - возвращает первый элемент из очереди и удаляет его, first() - возвращает первый ### элемент из очереди, не удаляя.
3. (task3) Напишите постфиксный калькулятор. Пользователь вводит данные и операции в обратной польской записи. Калькулятор вычисляет результат ### и проверяет, что в стэке получилось единственное число.

HomeWork005 (Домашнее задание к пятому семинару)
1. Написать простой класс ТелефонныйСправочник, который хранит в себе
список фамилий и телефонных номеров. В этот телефонный справочник с помощью
метода add() можно добавлять записи. С помощью метода get() искать номер
телефона по фамилии. Следует учесть, что под одной фамилией может быть
несколько телефонов (в случае однофамильцев), тогда при запросе такой
фамилии должны выводиться все телефоны.
Желательно как можно меньше добавлять своего, чего нет в задании (т.е.
не надо в телефонную запись добавлять еще дополнительные поля
(имя, отчество, адрес), делать взаимодействие с пользователем через
консоль и т.д.). Консоль желательно не использовать (в том числе Scanner),
тестировать просто из метода main() прописывая add() и get().

HomeWork006 (Домашнее задание к шестому семинару)
1. Создайте множество, в котором будут храниться экземпляры класса Cat - HashSet<Cat>. Поместите в него некоторое количество объектов.

2. Создайте 2 или более котов с одинаковыми параметрами в полях. Поместите их во множество. Убедитесь, что все они сохранились во множество.

3. Создайте метод