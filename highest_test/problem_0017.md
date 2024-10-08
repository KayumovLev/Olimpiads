# Задача 17

### Условие
Попарно различные натуральные числа $a, b, c, d$ таковы, что графики функций
$у=х^2–ах+b$ и $у=х^2–сх+d$ пересекаются в точке с координатами $(3; 1)$. Какое
наименьшее значение может принимать наибольшее из чисел $b$ и $d$?
### Решение
- Данная задача на подставление и выведение переменных
- Начнем с того, что составим объеденим все, помним, что $(x, y)$, следовательно $1 = 3^2-3a+b = х^2–3с+d$, отсюда можно вывести, что $b \equiv d \equiv 1(\mod 3)$, чтобы это понять приведем следющие равенства:
1. Для b $3^2-3a + b = 1 ; b = -9 + 1 + 3a; b = -8 + 3a$, так как число 3k(где k некое число) всегда будет делиться на три то можем его опустить и получить $b = -8 \Rightarrow b \equiv 1(\mod 3)$
2. Анологично для d $d = -8 \Rightarrow b \equiv 1 (\mod 3)$
Теперь нам ничего не мешает утверждать или по математически с точностью до симметрии, что $d > b$, следовательно отсюда можем понять, что минимально значение для $d$ будет $4$, отсюда $b = d - 3 = 1$, теперь найдем в данном случае значения $a$ и $c$: $b = -8 + 3a; -8 + 3a = 1; 3a = 9; a = 3$ и $d = -8 + 3c; -8 + 3c = 4; 3c = 12; c = 4; с = d$ - противоречит условию, теперь пробуем $d = 7$ и получаем такие значения $a = 3, b = 1, c = 5, d = 7$ 
### Ответ
- $7$