# Лабораторная работа №2 по Инструментальным средствам разработки ПО

## Описание
В проекте содержатся набор программ на Python для вычисления площадей и периметров фигур.

### Список файлов 
- `README.md`
- `circle.py`
- `rectangle.py`
- `square.py`
- `triangle.py`

### Клонирование репозитория
``` bash
https://github.com/vishka-vinka/lab2_isrpo.git
cd lab2_isrpo
```

### Функции
#### circle.py
def area(r):
    ''' 
    Принимает радиус круга и возвращает его площадь
    Параметр:
        r (int): радиус
    Возвращаемое значение:
        math.pi * r * r (float): площадь круга
    
    '''
    return math.pi * r * r


def perimeter(r):
    ''' 
    Принимает радиус окружности и возвращает её длину (периметр) 
    Параметр:
        r (int): радиус
    Возвращаемое значение:
        2 * math.pi * r (float): длина окружности (периметр)
    '''
    return 2 * math.pi * r

#### rectangle.py
def area(a, b):
    ''' 
    Принимает длину двух сторон прямоугольника и возвращает его площадь 
    Параметры:
        a (int): длина одной из сторон прямоугольника
        b (int): длина другой стороны прямоугольника
    Возвращаемое значение:
        a*b (int): площадь прямоугольника
    '''
    return a*b

def perimeter(a, b):
    ''' 
    Принимает длину двух сторон прямоугольника и возвращает его периметр 
    Параметры:
    a (int): длина одной из сторон прямоугольника
    b (int): длина другой стороны прямоугольника
    Возвращаемое значение:
        2 * (a+b) (int): периметр прямоугольника
    '''
    return 2 * (a+b)

#### square.py
def area(a):
    '''
    Принимает длину стороны квадрата и возвращает его площадь
    Параметр:
        a (int): длина стороны квадрата
    Возвращаемое значение:
        a * a (int): площадь квадрата
    '''
    return a * a


def perimeter(a):
    '''
    Принимает длину стороны квадрата и возвращает его периметр
    Параметр:
        a (int): длина стороны квадрата
    Возвращаемое значение:
        4 * a (int): периметр квадрата
    '''
    return 4 * a

#### triangle.py
def area (a, h):
    '''
    Принимает высоту и сторону треугольника, на которую падает эта высота, и возвращает его плошадь
    Параметры:
        a (int): длина стороны треугольника
        h (int): длина высоты треугольника, падающей на сторону, длина которой указана в а
    Возвращаемое значение:
        a*h/2 (float): площадь треуголька
    '''
    return a*h/2

def perimeter (a, b, c):
    '''
    Принимает длины трёх сторон треугольника и возвращает его периметр
    Параметры:
        a (int): длина первой стороны треугольника
        b (int): длина второй стороны треугольника
        c (int): длины третей стороны треугольника
    Возвращаемое значение:
        a+b+c (int): периметр треугольника
    '''
    return a+b+c

### История коммитов
- Initial commit d43ea64
- add: create circle.py 06a2498
- add: create rectangle.py 26c41fb
- Create square.py 3af8ef3
- add: create triangle.py 691dc39
- Create docs 4412463
- fix: rename docs to docs.txt c6ec544
- fix: update README.md d95757e
- fix: fix headlines b0d3a13
- fix: fix list of files d2ddbef
- fix: fix format of list in README 4542087
- fix: fix italics of files names 553ac43
- feat: add docs 3c52dd8
- fix: delete docs.txt 3b91fbd
- fix: move Readme to docs 7767792
- fix: delete docs/gitkeeper.txt 5d563a0
- fix: add description for functions in circle.py b876f39
- fix: add description for functions in rectangle.py 2b4a5da
- fix: add description for functions in square.py e868d4c
- fix: add description for functions in triangle.py 597a7b4
- fix: update circle's description of functions 0ce8a98
- fix: update rectangle's description of functions 1c08539
- fix: update square's description of functions 083629c
- fix: update triangle's description of functions f721459
### Автор
Матафонова Виктория Евгеньевна 561864
