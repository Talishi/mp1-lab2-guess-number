# Репозиторий для сдачи лабораторной работы №2.

## Разработать программу «Угадай число».<br/>
В программе должно быть предусмотрено два режима.<br/>
**Режим 1.** Программа «загадывает» случайное число из диапазона **от 1 до 1000**. Пользователь должен вводить отгадки, на которые программа сообщает: «загаданное число больше», «загаданное число меньше», «угадали». Работа завершается, когда пользователь угадает число. Также программа должна подсчитывать **число попыток** и выводить его в конце работы.<br/>

**Режим 2.** Пользователь загадывает число из диапазона **от 1 до 1000** и вводит его. Программа пытается «угадать» число, выводя на экран отгадки, на которые пользователь вводит >, < или =. Работа завершается, когда программа угадает число. Также программа должна подсчитывать **число попыток** и выводить его в конце работы.<br/>

Для генерации псевдослучайных чисел, необходимо использовать функцию **rand()** из библиотеки **<stdlib.h>**.<br/>

int a = rand(); // генерация псевдослучайного числа<br/>
int b = rand() % N; // генерация псевдослучайного числа в диапазоне от 0 до N<br/>
int c = M + rand(); // генерация псевдослучайного числа в диапазоне от M до RAND_MAX<br/>
int d = M + rand() % (N - M + 1) // генерация псевдослучайного числа в диапазоне [M, N]<br/>
