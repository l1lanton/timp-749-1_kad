#pr1_01_hello
Программа, печатающая в stdout фразу "Hello, World!" на отдельной строке.

#pr1_02_sum
Программа, принимающая на вход два числа, разделённые пробелом, и суммирующую их. Ввод чисел производить из stdin, вывод результата - в stdout. Вводимые числа не превосходят по модулю 2147483647.

#pr1_03_pow
Программа, принимающая на вход числа x и y, разделённые пробелом, и вычисляющую x в степени y. Ввод чисел производить из stdin, вывод результата - в stdout. Вводимые числа не превосходят по модулю 2147483647. Реализовывать возведение в степень через цикл/рекурсию не допускается

#pr2_07_count_negative
Количество отрицательных чисел:
На вход подаётся
число 𝑛 ∈ N : 𝑛 ≤ 2147483647, а также 𝑛 чисел 𝑥𝑖 ∈ Z : |𝑥𝑖
| ≤ 2147483647
для любого целого 𝑖 от 1 до 𝑛. Вывести количество чисел 𝑥𝑖
: 𝑥𝑖 < 0.

#pr2_17_diff_betw_even_and_odd_squares
Разность сумм нечётных и чётных кубов:
На
вход подаётся число 𝑛 ∈ N : 𝑛 ≤ 2147483647, а также 𝑛 чисел 𝑥𝑖 ∈
Z : |𝑥𝑖
| ≤ 2147483647 для любого целого 𝑖 от 1 до 𝑛. Вывести значение
∑︁𝑛
𝑖=1
(−1)𝑖
· 𝑥
2
𝑖
.
.

#pr3_01_lists 
Программа, которая:
1.	считывает количество элементов n, 0 < n <= 2147483647;
2.	создает пустой список, считывает n элементов a, |a| <= 2147483647 и заносит их в список;
3.	выводит содержимое списка, используя функцию print;
4.	считывает k1, k2, k3 (|k| <= 2147483647) и выводит "1", если в списке существует элемент с таким значением и "0", если нет (выводить через пробел, например "1 0 1");
5.	считывает m, |m| <= 2147483647 и вставляет его в конец списка;
6.	выводит содержимое списка, используя функцию print;
7.	считывает t, |t| <= 2147483647 и вставляет его в начало списка;
8.	выводит содержимое списка, используя функцию print;
9.	считывает j и x (0 < j <= 2147483647, |x| <= 2147483647) и вставляет значение x после j-ого элемента списка;
10.	выводит содержимое списка, используя функцию print;
11.	считывает z, |z| <= 2147483647 и удаляет первый элемент (при его наличии), хранящий значение z из списка;
12.	выводит содержимое списка, используя функцию print;
13.	очищает список.

#pr4_01_lists
Программа, которая:
1.	считывает количество элементов n, 0 < n <= 2147483647;
2.	создает пустой список, считывает n элементов a, |a| <= 2147483647 и заносит их в список;
3.	выводит содержимое списка, используя функцию print;
4.	считывает k1, k2, k3 (|k| <= 2147483647) и выводит "1", если в списке существует элемент с таким значением и "0" если нет (выводить через пробел, например "1 0 1");
5.	считывает m, |m| <= 2147483647 и вставляет его в конец списка;
6.	выводит содержимое списка, используя функцию print_invers;
7.	считывает t, |t| <= 2147483647 и вставляет его в начало списка;
8.	выводит содержимое списка, используя функцию print;
9.	считывает j и x (0 < j <= 2147483647, |x| <= 2147483647) и вставляет значение x после j-ого элемента списка;
10.	выводит содержимое списка, используя функцию print_invers;
11.	считывает u и y (0 < u <= 2147483647, |y| <= 2147483647) и вставляет значение y перед u-ым элементом списка;
12.	выводит содержимое списка, используя функцию print;
13.	считывает z, |z| <= 2147483647 и удаляет первый элемент (при его наличии), хранящий значение z из списка;
14.	выводит содержимое списка, используя функцию print_invers;
15.	считывает r, |r| <= 2147483647 и удаляет последний элемент (при его наличии), хранящий значение r из списка;
16.	выводит содержимое списка, используя функцию print;
17.	очищает список.

#pr5_01_bst
Программа, которая:
1.	создает пустое дерево, считывает 4 элемента ai, |ai| <= 2147483647 и заносит их в дерево;
2.	выводит дерево (используя функцию print_tree) и пустую строку;
3.	считывает 3 элемента ai, |ai| <= 2147483647 и заносит их в дерево;
4.	выводит дерево и пустую строку;
5.	считывает m1, |m1| <= 2147483647 и ищет элемент с заданным значением в дереве; выводит через пробел значение предка и потомков найденного элемента, если нет значений предка или потомков вывести "_" вместо таких значений; вывести "-", если элемент не найден; вывести пустую строку;
6.	считывает m2, |m2| <= 2147483647 и ищет элемент с заданным значением в дереве; выводит через пробел значение предка и потомков найденного элемента, если нет значений предка или потомков вывести "_" вместо таких значений; вывести "-", если элемент не найден; вывести пустую строку;
7.	считывает m3, |m3| <= 2147483647 и удаляет из дерева элемент с заданным значением (если такой элемент есть);
8.	выводит дерево и пустую строку;
9.	выполняет левый поворот дерева относительно корня, пока это возможно;
10.	выводит дерево и пустую строку;
11.	выполняет правый поворот дерева относительно корня, пока это возможно;
12.	выводит дерево и пустую строку;
13.	выводит на экран количество элементов в дереве и пустую строку
14.	очищает дерево
15.	выводит дерево и пустую строку;

#pr6_01_width
Программа обхода дерева в ширину.

#pr6_02_straight
Программа прямого обхода дерева.

#pr6_03_back.c
Программа обратного проъода дерева.
