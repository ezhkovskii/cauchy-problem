# -
Усовершенствованный метод Эйлера – Коши с итерационной обработкой с уточнением по правилу Рунге для задачи Коши ОДУ 1 порядка.
_________________________________________________________________________________________________________________________________
Постановка задачи
Перед нами стоит задача изучить усовершенствованный метод Эйлера- Коши для решения задачи Коши для обыкновенных дифференциальных уравнений. 
Дано ОДУ 1 порядка:
y’ = (-3yx+8y-x^2)/(x^2-5x+6); 
y(0)= -1;
x ∈ [0,1];
h = 0.1;

Точное решение: y=(-1/4*x^4+2/3*x^3+12)/((x-2)^2 *(x-3));

В коде ОДУ решено методом Эйлера и усовершенствованном методом Эйлера- Коши.
В конце выводится решения этих методов и точное решение для сравнения.
