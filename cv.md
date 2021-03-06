# Rinat Miniyarov
* https://t.me/rinatminiy
* rinatminiy@gmail.com

## About me

* The goal is simple - go to work in web developmen, no more no less. 
* I am studying to be an engineer in the design of aircraft and rocket engines, but I plan to work as a React-developer.From the university, I brought out a baggage of knowledge that will help me on this path (the ability to study new information, an engineering approach to solving problems, basic knowledge of mathematics and physics). I got acquainted with programming, in fact, thanks to a scientific project at the university, during which it was necessary to write a program in Python for calculating with a parameter in the combustion chamber of an aircraft. After this experience, I realized what I want to do.

## Skills

* HTML/CSS
    * Less
    * bootstrap
* JS
* Python
    * Numpy
    * Matplotlib
    * Pandas
* Git

## Code 

**Input** - number

**Output** - table of size n*n filled with numbers from 1 to n**2  in a spiral starting from the upper left corner and twisted clockwise

```
n = int(input())
m = [[0] * n for i in range(n)]
i, j, di, dj = 0, 0, 0, 1

for k in range(n * n):
    m[i][j] = k + 1
    if (not -1 < i + di < n) or (not -1 < j + dj < n) or m[i + di][j + dj] != 0:
        di, dj = dj, -di
    i, j = i + di, j + dj

[print(*i) for i in m]
```

## Education

* JS - Современный учебник JavaScript
* HTML/CSS - FreeCodeCamp courses
* Python - courses from Stepik 

## English 

A2 (Previously, the level was definitely higher, but the lack of practice in speaking and writing affected. But listening and reading are at a high level, because of a lot of information I learn in English)
