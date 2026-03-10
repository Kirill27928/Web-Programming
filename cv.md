---
layout: default
---

CV
==

Kirill Sazonov
--------------

![](image.jpg)

Contacts
--------

*   Phone: +375259885133
*   Mail: kirillsazonov@gmail.com

About me
--------
I am second-year student PMR-241 at the Belarusian-Russian University.

Example code
------------
```c++
    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    #include <stdlib.h>
    #define SIZE 6
    int main()
    {
    int a[SIZE][SIZE]; // матрица связей
    int d[SIZE]; // минимальное расстояние
    int v[SIZE]; // посещенные вершины
    int temp, minindex, min;
    int begin_index = 0;
    system("chcp 1251");
    system("cls");
    // Инициализация матрицы связей
    for (int i = 0; i < SIZE; i++)
    {
        a[i][i] = 0;
        for (int j = i + 1; j < SIZE; j++) {
        printf("Введите расстояние %d - %d: ", i + 1, j + 1);
        scanf("%d", &temp);
        a[i][j] = temp;
        a[j][i] = temp;
        }
    }
    // Вывод матрицы связей
    for (int i = 0; i < SIZE; i++)
    {
        for (int j = 0; j < SIZE; j++)
        printf("%5d ", a[i][j]);
        printf("\n");
    }
    //Инициализация вершин и расстояний
    for (int i = 0; i < SIZE; i++)
    {
        d[i] = 10000;
        v[i] = 1;
    }
    return 0;
    }
```

Work experience
---------------
Application of differential equations in physicals processes. My work focused on translating the laws of classical mechanics into math models.

My courses
----------

*   C++
*   Python
*   English

English level
-------------
*   B2


