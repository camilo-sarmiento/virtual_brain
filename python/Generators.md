# Generators
> *Generadores*

Lo **generadores** son parecidos a los [[Python#Bucles| Bucles]], donde se utiliza un [[Python#Iterator | iterator]] en un [[Python#Iterable | iterable]] y se obtiene una [[Python#Iteration | iteration]] que podemos devolver con el **yield**.



Pero en los generadores, la [[Python#Iteration|iteración]] no se guarda en memoria, los cuales se pueden invocar con la función **next()**, esto permite que sean mas óptimos.

```jupyter
import sys
def fibo(z) -> int:
	x = 0
	y = 1
	for i in range(z):
		yield x
		x, y = y, x + y
gen = fibo(10)

for i in range(5):
	print(next(gen))
	
```

<br/>

---
## yield

Este es como un **return** que devuelve el valor, pero este no detiene la función.

<br/>

---
## yield from

Este hace lo mismo que un **yield**, pero se usa para hacer un [[Python#Iterator | iterador]] con el elemento que se le asigna, por ejemplo:

```jupyter
def yield_from(x = 'python'):
	for i in x:
		yield from i
		
gen = yield_from()

for i in range(4):
	print(next(gen))
```