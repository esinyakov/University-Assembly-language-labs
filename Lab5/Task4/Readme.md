Task4 Make a program of two source modules. Module 1 should contain descriptions of the STK stack segment, the SD1 data segment (with the variable X DB 'X') and the description part of the SC1 code segment. Module 2 must contain a description of the data segment SD2 (with variable Y DB 'Y') and another part of the description of the data segment SC2. Management should get Module 1 and immediately transfer control to Module 2 using the JMP command. In Module 2, you should change the values of the variables X and Y, and display the value of the variable Y (that is, the 'Y' character) using the DOS function 2 and exit the program using the INT 21h function 4Ch.

Задание4 Составить программу из двух исходных модулей. Модуль 1 должен содержать описания сегмента стека STK, сегмента данных SD1 (с переменной X DB 'X') и части описания сегмента кода SC1. Модуль 2 должен содержать описание сегмента данных SD2 (с переменной Y DB 'Y') и другой части описания сегмента данных SC2. Управление должен получить Модуль 1 и сразу передать управление в Модуль 2 командой JMP. В Модуле 2 следует поменять значения переменных X и Y, и вывести значение переменной Y (т.е. символ 'Y') по функции 2 DOS и выйти из программы по функции 4Ch команды INT 21h.