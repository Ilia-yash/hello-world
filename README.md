import math
import cmath
x=input().split()
a = float(x[0])
b = float(x[1])
c = float(x[2])
 
discr = b ** 2 - 4 * a * c
 
if discr > 0:
    x1 = (-b + math.sqrt(discr)) / (2 * a)
    x2 = (-b - math.sqrt(discr)) / (2 * a)
    print(x1, x2)
if discr == 0:
    x = -b / (2 * a)
    print(x)
if discr<=0:
    x1 = (-b + cmath.sqrt(discr)) / (2 * a)
    x2 = (-b - cmath.sqrt(discr)) / (2 * a)
    print(x1, x2)
    
print(d)

