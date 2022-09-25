# Why-do-you-need-parentheses-in-programs
__Зачем нужны скобки в программах!__

*(2+3)/(4+6) = 0.5*

![srcreenshot](screenshot1.jpg)

*2+3/(4+6) = 2.3*

![srcreenshot](screenshot2.jpg)

*(2+3)/4+6 = 7.25*

![srcreenshot](screenshot3.jpg)

*2+3/4+6 = 8.75*

![srcreenshot](screenshot4.jpg)

*(2\*3)/(4\*6) = 0.25*

![srcreenshot](screenshot5.jpg)

*(2\*3)/4\*6 = 9*

![srcreenshot](screenshot6.jpg)

***Программа на Python для сомнивающихся: ))***
```
a = 2
b = 3
c = 4
d = 6
x1 = (a + b) / (c + d)
x2 = a + b / (c + d)
x3 = (a + b) / c + d
x4 = a + b / c + d
x5 = (a * b) / (c * d)
x6 = (a * b) / c * d
print(x1)
print(x2)
print(x3)
print(x4)
print(x5)
print(x6)
```

