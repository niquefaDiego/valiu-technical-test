
# Problema 1. Celadores

El conjunto de David necesita celadores para los siguientes $m$ ($1 \leq m \leq 10^6$) días, los días están enumerados del $1$ al $m$. El conjunto tiene $n$ ($1 \leq n \leq 10^6$)  celadores, el celador $i$ esta disponible para cuidar el conjunto desde el día $a_i$ hasta el día $b_i$, inclusive ($1 \leq a[i] \leq b[i] \leq m$). ¿Cuántos de los siguientes $m$ días pueden tener celador?

## Ejemplo

### Entrada

$n=3$
$m=10$
$A = [1, 2, 8]$
$B = [4, 5, 9]$

### Salida

7

### Explicación

Los días 1, 2, 3, 4, 5, 8 y 9 pueden tener celador. Pero ningún celador está disponible los días 6, 7 y 10.

# Problema 2. Contar pares mal ordenados

Dado un arreglo $a$ de $n$ ($n <= 10^6$) números enteros diferentes. ¿Cuántas parejas de índices $(i,j)$ hay que cumplen: $i < j$ y $a_i > a_j$?

## Ejemplo

### Entrada
$a = [1, 3, 2, 5, 4]$

### Salida
2
### Explicación
Las parejas dos son:
- $i=1, j=2, a_i=3, a_j=2$
- $i=3, j=4, a_i=5, a_j=4$

# Problem 3. Caballo

Dado que tenemos un tablero de ajedrez infinito. Hacer un programa que determine el mínimo número de movimientos que un caballo debe hacer para llegar de las coordenadas $(a,b)$ a las coordenadas $(c,d)$. Note que las coordenadas pueden ser negativas y grandes:  $-10^6 \leq a, b, c, d \leq 10^6$

## Ejemplo

### Entrada
$a=-5, b=-5, c=5, d=5$

### Salida
8

### Explicación:
Uno de los posibles caminos con 8 movimientos:
$(-5,-5)$ &rarr; $(-4,-3)$ &rarr; $(-2,-2)$ &rarr; $(0,-1)$ &rarr; $(1,1)$ &rarr; $(3,2)$ &rarr; $(4,4)$ &rarr; $(3,6)$ &rarr; $(5,5)$
