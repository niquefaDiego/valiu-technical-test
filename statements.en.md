# Problem 1. Watchmen

David's residential complex needs a watchman for each of the next $m$ ($1 \leq m \leq 10^6$) days, days are numbered from $1$ to $m$. The complex has $n$ ($1 \leq n \leq 10^6$) watchmen, watchman $i$ is only available to work from day $a_i$ until day $b_i$, inclusive ($1 \leq a[i] \leq b[i] \leq m$). How many of the next $m$ days can have a watchman on duty?

## Example

### Input

$n=3$
$m=10$
$A = [1, 2, 8]$
$B = [4, 5, 9]$

### Output
7

### Explanation

Days 1, 2, 3, 4, 5, 8 y 9 can have a watchman. But no watchman is available on days 6, 7 y 10.

# Problem 2. Count misordered pairs

Given an array $a$ of $n$ ($n <= 10^6$) distinct integer numbers. How many pairs of indexes $(i,j)$ are there such that $i < j$ and $a_i > a_j$?
  

## Example

### Input

$a = [1, 3, 2, 5, 4]$

### Output

2

### Explanation

The pairs are:

- $i=1, j=2, a_i=3, a_j=2$
- $i=3, j=4, a_i=5, a_j=4$

# Problem 3. Knight

Given that we have an infinite chess board. You need to write a program to determine the minimum number of movements a Knight must do to get from coordinates $(a,b)$ to coordinates $(c,d)$. Note that coordinates can be negative and quite big: $-10^6 \leq a, b, c, d \leq 10^6$

## Example
  
### Input

$a=-5, b=-5, c=5, d=5$

### Output

8

### Explanation

Here is one of the possible 8 movement paths:

$(-5,-5)$ &rarr; $(-4,-3)$ &rarr; $(-2,-2)$ &rarr; $(0,-1)$ &rarr; $(1,1)$ &rarr; $(3,2)$ &rarr; $(4,4)$ &rarr; $(3,6)$ &rarr; $(5,5)$
