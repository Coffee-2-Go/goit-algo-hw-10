# Висновок:

У данній роботі було проведено порівняння результатів обчислення інтегралу функції 
$𝑓(𝑥) = 𝑥^2$ від $𝑥=0$ до $x=2$ за допомогою методу Монте-Карло та функції quad з підмодуля integrate бібліотеки SciPy.

Значення інтеграла отримане методом Монте-Карло дуже близьке до точного значення інтеграла, обчисленого за допомогою функції quad:
- значення інтеграла отримане методом Монте-Карло: 2.680741983042183. Абсолютна похибка: 0.014, відносна похибка - 0.53%
- значення інтеграла отримане за допомогою функції quad: 2.666666666666667.
- аналітичне значення визначеного інтеграла:

$$ \int_0^2 f(x^2) \;dx = \frac{x^3}{3} \Big|_0^2 = \frac{2^3}{3} - 0 = 2.66(6)$$
 
Отримані результати підтверджують, що метод Монте-Карло забезпечує досить точне обчислення інтегралів. 

Хоча метод Монте-Карло має невелику похибку, він може бути особливо корисним для складних або незамкнених функцій, де аналітичні методи важко застосувати.

Таким чином, площа під графіком (сіра зона) становить приблизно 2.67 за методом Монте-Карло і точно 2.66(6) за аналітичним методом та функцією quad.
