# Solver of quadratic equations

This project is designed to solve quadratic equations

# How to use



#####def get_roots(a, b, c)
This function calculates the discriminant and finds the roots finds the roots of the quadratic equation. arguments. numerical.
```
def get_roots(a, b, c):
    discriminant = b ** 2 - 4 * a * c
    if discriminant < 0:
        root1 = (-b - cmath.sqrt(discriminant)) / (2 * a)
        root2 = (-b + cmath.sqrt(discriminant)) / (2 * a)
        return None, None
    else:
        root1 = (-b - sqrt(discriminant)) / (2 * a)
        root2 = (-b + sqrt(discriminant)) / (2 * a)
        if discriminant == 0:
            return root1, None
        else:
            return root1, root2

```
# How to start

The script requires the installed Python interpreter version 3.5

Running on Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

the launch on Windows is similar.

# Project Objectives

The code was created for educational purposes. In the framework of the training course on web development ― [DEVMAN.org](https://devman.org)
