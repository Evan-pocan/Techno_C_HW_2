# Вариант 10
В вашем распоряжении — массив из 100 млн. чисел. Составьте наивный алгоритм подсчета суммы [k+ 10i]-х элементов для каждого k = 1, 10 (i = 0, 10000000), после чего реализуйте параллельный алгоритм на нескольких процессах с учетом оптимизации работы с кэш-памятью.

# Результаты работы
_Ниже продемонстрированно среднее арифметическое по выборке из 4 тестов_
## Последовательная реализация
Result: 450020061

Time: 1.199794 с
## Параллельная реализация
Result: 450020061

Time: 0.433080 с
