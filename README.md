# Репозиторий для сдачи домашних заданий по курсу Java
## HW1 (Домашнее задание по первому семинару)

1. (task1) Вычислить n-ое треугольного число(сумма чисел от 1 до n), n!
2. (task2) Вывести все простые числа от 1 до 1000
3. (task3) Реализовать простой калькулятор
4. (task4) Задано уравнение вида q + w = e, q, w, e >= 0. Некоторые цифры могут быть заменены знаком вопроса, например 1? + ?5 = 69.
Требуется восстановить выражение до верного равенства. Предложить хотя бы одно решение или сообщить, что его нет.

## HW2 (Домашнее задание по второму семинару)

1. (Task1_1) Дана строка sql-запроса "select * from students where ". Сформируйте часть WHERE этого запроса, используя StringBuilder. Данные для фильтрации приведены ниже в виде json-строки.
Если значение null, то параметр не должен попадать в запрос.
Параметры для фильтрации: {"name":"Ivanov", "country":"Russia", "city":"Moscow", "age":"null"}
2. (Task2_1) Необязательно. Реализуйте алгоритм сортировки пузырьком числового массива, результат после каждой итерации запишите в лог-файл.
3. (Task3_1) Дана json-строка (можно сохранить в файл и читать из файла)
[{"фамилия":"Иванов","оценка":"5","предмет":"Математика"},{"фамилия":"Петрова","оценка":"4","предмет":"Информатика"},{"фамилия":"Краснов","оценка":"5","предмет":"Физика"}]
Написать метод(ы), который распарсит json и, используя StringBuilder, создаст строки вида: Студент [фамилия] получил [оценка] по предмету [предмет].
Пример вывода:
Студент Иванов получил 5 по предмету Математика.
Студент Петрова получил 4 по предмету Информатика.
Студент Краснов получил 5 по предмету Физика.

## HW3 (Домашнее задание по третьему семинару)

Пусть дан произвольный список целых чисел.

1. Нужно удалить из него чётные числа
2. Найти минимальное значение
3. Найти максимальное значение
4. Найти среднее значение

## HW4 (Домашнее задание по четвертому семинару)

1. Пусть дан LinkedList с несколькими элементами. Реализуйте метод, который вернет “перевернутый” список.
2. Реализуйте очередь с помощью LinkedList со следующими методами:
enqueue() - помещает элемент в конец очереди, dequeue() - возвращает первый элемент из очереди и удаляет его, first() - возвращает первый элемент из очереди, не удаляя.
3. Не обязательно, для тех кто хочет посложнее. Реализовать очередь из задания 2 но на основе массива.
