# description
maht lib with perimeter and area functions to circle, square, triangle, rectangle

---

# function notation

## Circle.py
>\# area function
>\#  area counting by radius
>\#   args:
>\#       int r : circle radius
>\#   return:
>\#       int : area of circle with radius r
> def area(r)

>\# perimeter function
>\#  perimeter counting by radius
>\#   args:
>\#       int r : circle radius
>\#   return:
>\#       int : perimeter of circle with radius r
>def perimeter(r)

---

## Rectangle.py
> \# area function
> \#  area counting of rectangle
> \#   args:
> \#       int a : widths
> \#       int b : height
> \#   return:
> \#       int : area of rectangle with lenths a;b
> def area(a, b)

> \# perimeter function
> \#  perimeter counting of triangle
> \#   args:
> \#       int a : side of base
> \#       int b : side of base
> \#       int c : side of base
> \#   return:
> \#       int : perimeter of triangle with sides a;b;c
> def perimeter(a, b)

---

## Square.py
> \# area function
> \#  area counting of square
> \#   args:
> \#       int a : widths
> \#   return:
> \#       int : area of square with lenths a
> def area(a)

> \# perimeter function
> \#  perimeter counting of square
> \#   args:
> \#       int a : widths
> \#   return:
> \#       int : perimeter of square with lenths a
> def perimeter(a)

---

## Triangle.py
> \# area function
> \#  area counting of triangle
> \#   args:S
> \#       int a : widths pf base
> \#       int h : height
> \#   return:
> \#       int : area of triangle with lenths a
> def area(a, h)

> \# perimeter function
> \#  perimeter counting of triangle
> \#   args:
> \#       int a : widths pf base
> \#       int h : height
> \#   return:
> \#       int : perimeter of triangle with lenths a ; height h
> def perimeter(a, b, c)

---

# Examples
### Circle
```py
# -------------
x = area(2)
# x === 13
# -------------
y = perimeter(2)
# y === 13
```

### Rectangle
```py
# -------------
x = area(2, 3)
# x === 6
# -------------
y = perimeter(2, 3)
# y === 10
```

### Square

```py
# -------------
x = area(2)
# x === 4
# -------------
y = perimeter(2)
# y === 8
```

### Triangle
```py
# -------------
x = area(2, 1)
# x === 1
# -------------
y = perimeter(2, 3, 4)
# y === 9
```

---

# Project changes history

```fimos
* 72166aae2e4ac144e8f8057dc20dbc78e1e98d23 (HEAD -> new_feature_467005) End math lib. With comments
| * 86edb1c3dd57fa9abc7ba2ec7052507938084727 (origin/release) L-05: Update Docs. Add user agreement info
| * 438b89a1dfc58d90e9036fe431771427965cd1ff L-05: Add user agreement
| * 6adb96248a4d00d3bea13bd95d78ef52352cd1b4 L-03: Docs added
| | * 30494317cde4419be779c14306561e0eaa78b88b (origin/feature) L-04: Add rectangle.py
| |/
|/|
| | * b5b0fae727ca72c317c383b39c0af73d6adcd81c (origin/develop) L-04: Update docs for calculate.py
| | * d76db2ac7f69cc920ae2e6f669fb0671a7fa7d71 L-04: Add calculate.py
| | * 51c40ebfd0e0b65f52fe5e54740cbb038e492db3 L-04: Doc updated for triangle
| | * d080c7888b81955bad2ed78d58ad910526b5132a L-04: Triangle added
| |/
|/|
* | d078c8d9ee6155f3cb0e577d28d337b791de28e2 (origin/main, origin/HEAD, main) L-03: Docs added
|/
* 8ba9aeb3cea847b63a91ac378a2a6db758682460 L-03: Circle and square added
```
---

# Math Formuls

## Area

- Circle: $S = πR²$
- Rectangle: $S = ab$
- Square: $S = a²$
- Triangle: $S = (a * h) / 2$

## Perimeter
- Circle: $P = 2πR$
- Rectangle: $P = 2a + 2b$
- Square: $P = 4a$
- Triangle: $P = a + b + c$