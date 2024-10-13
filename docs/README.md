
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`
- Triangle: *S = sqrt(p * (p-a) * (p-b) * (p-c))' where p is semiperimeter
# Общее описание решения
## Square
- Задавая одну сторону находит площадь квадрата и его периметр
## Circle
- Задавая радиус находит площадь круга и его периметр
# Описание каждой функции с примерами вызова
## Функции для квадрата ### area(a) - Нахождение площади квадрата
- Принимает число а (одну из сторон), возвращает квадрат числа а (его площадь)
```
python 
def area(a):
#（a = 5）
return a * a
#(вернет число 25)
```
### perimeter(a) - Нахождение периметра квадрата
- Принимает число а (одну из сторон), возвращает число а умноженное на 4 (его периметр)
```
python def 
perimeter(a):
return 4 * a
#(a = 5)
#(вернет число 20)
```
## Функции для круга
### area(a)
- Принимает число т (радиус круга), возвращает число п * г (площадь круга)
```
python 
def area(r):
#(a = 4)
return math.pi * I * I 
#(вернет число 50,24)
```
### perimeter（r）
Принимает число т (радиус круга), возвращает число 2 * п * г (периметр круга)
```
python 
def perimeter(r):
#（a=4）
return 2 * math.pi * r
#(вернет число 25,12)
```
## L-03
- L-03: Docs added **438b89a**
- L-03: Circle and square added **8ba9aeb**
## L-04
- L-04: Add rectangle.py **3049431**
- L-04: Add calculate.py **d76db2a**
- L-04: Doc updated for triangle **51c40eb**
- L-04: Triangle added **d080c78**
- ## L-05
- L-05: Add user agreement **438b89a**
- L-05: Update Docs. Add user agreement info **86edb1c**