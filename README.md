# Reto4
### Repo sobre el Reto 4, donde se trabajó en una notebook de Python sobre diferentes problemas

#### 1.
```python
n = input("Escribe un número entero: ")     
if n == "97":
     print("Sí, es " + chr(int(n)))  
elif n == "101":
     print("Sí, es " + chr(int(n)))
elif n == "105":
     print("Sí, es " + chr(int(n)))
elif n == "111":
     print("Sí, es " + chr(int(n)))
elif n == "117":
     print("Sí, es " + chr(int(n)))
else:
     print("No corresponde a ninguna vocal")
```
#### 2.
```python
n = input("Escribe una letra: ")
z = ord(n) % 2 

if z == 0:
    print("El codigo ASCII de " + n + " es par")
else:
    print("El código ASCII de " + n + " no es par")
```
#### 3.
```python
m = input("Escribe un carácter: ")
if m.isdigit():
    print(str(m) + " es un dígito.")
else:
    print(str(m) + " no es un dígito.")
```
#### 4.
```python
n = float(input("Escribe un número: "))
if n > 0:
    print("El número " + str(n) + " es positivo")
elif n == 0:
    print("El número " + str(n) + " es el neutro para la suma")
else:
    print("El número " + str(n) + " es negativo")
```
#### 5.
```python
m = float(input("Escribe la coordenada 'x' del punto: "))
n = float(input("Escribe la coordenada 'y' del punto: "))
x = float(input("Escribe la coordenada 'x' del centro: "))
y = float(input("Escribe la coordenada 'y' del centro: "))
z = float(input("Escribe el radio del círculo: "))

if z**2 > (m - x)**2 + (n - y)**2:
    print("El punto (" + str(m) + ", " + str(n) + ") pertenece al interior del círculo")
else:
    print("El punto (" + str(m) + ", " + str(n) + ") no pertenece al interior del círculo")
```
#### 6.
```python
o = float(input("Escribe una longitud: "))
p = float(input("Escribe la segunda longitud: "))
q = float(input("Escribe la tercera longitud: "))
z = "se puede crear un triángulo"
if o < p + q and o > abs(p - q):
    print(z)
elif p < o + q and p > abs(o - q):
    print(z)
elif q < o + p and q > abs(o - p):
    print(z)
else:
    print("No se puede crear un triángulo")
```
