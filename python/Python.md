[[Unidades de medida]]
# Listas


```ad-example
 ['item_1', 'item_2', 'item_3', 'item_4', 'item_5', 'item_6']
```

Son contenedores en los cuales se pueden almacenar varios elementos de mismo o diferentes tipos de datos, además de que se pueden anidar listas.

```python
vocales = ['a', 'e', 'i', 'o', 'u']
lista = ['a', ['d', 'b'], 'z']
naturales = [1, 2, 3, 4, 5, 6, 7, 8, 9]
```

<br/>

---

# Tuplas

```ad-example
 ('item_1', 'item_2', 'item_3', 'item_4', 'item_5', 'item_6')
```

Son contenedores o mejor son bóvedas, los elementos que se guardan en una **tupla** al momento de declararlas **son inmutables**, esto quiere decir que no se pueden agregar, editar o adicionar.

```python
vocales = ('a', 'e', 'i', 'o', 'u')
lista = ('a', ['d', 'b'], 'z')
naturales = (1, 2, 3, 4, 5, 6, 7, 8, 9)
```
---

# Diccionarios
```ad-example
 {
 'Key_1' : 'Value_1',
 'Key_2' : 'Value_2',
 'Key_3' : 'Value_3',
 'Key_4' : 'Value_4',
 'Key_5' : 'Value_5',
 }
```

Los diccionarios son una estructura de datos, donde podemos almacenar diferentes tipos de elemento *(listas, tuplas, datos)*, donde los podemos combinara para guardar matrices.

Se caracterizan por tener un **llave** y un **valor**, los cuales se paran por *comas* y se encierran entre *corchetes { }*.

``` jupyter
dictionary = {
	'lenguaje' : ['py', 'js', 'c', 'c++', 'c#'],
	'age' : (20, 35, 61, 21, 25) 
}

data = dictionary.items()
print(dictionary['lenguaje'], dictionary['age'][0])
```

<br/>

---
 
<br/>

# Bucles


Los bucles se dividen en tres partes:
* Iterable *(Iterable)*
* Iterator *(Iterador)*
* Iteration *(iteracción)*

<br/>

## Iterable
> Elementos Iterables

Son objetos que están compuestos por varios elementos, los cuales un bucle puede recorrer, alguno de estos elementos son:

* [[Python#Listas | Listas]]
* [[Python#Tuplas | Tuplas]]
* [[Python#Diccionarios | Diccionarios]]
* [[Python#Strings | Strings]]
<br/>

## Iterator
> Objetos que recorren elementos

Son objetos que toman un **iterable** y recorre cada uno de sus elementos, los cuales podemos guardarlos.

``` jupyter
iter = [0, 1, 2, 3, 4, 5]

for i in range(len(iter)):
	print(f'iter number: {i}')
```

<br/>

## Iteration
> Resultado del **iterator**

Es el resultado de cada iteración que se realiza, este puede se igual al iterable o se puede modificar.

``` jupyter
iter = [0, 1, 2, 3, 4, 5]

for i in iter:
	print(i * 6, end = ' ')
```
<br/>
<br/>

---

# Lambda

Es una **función anónima**, donde no tiene nombre ni definición **def**, pero funciona con parámetros y retorna un valor.

```jupyter
func = lambda x: x*x

for i in range(5):
	print(func(i))
```