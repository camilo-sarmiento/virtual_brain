# Map

Este es un [[Python#Iterator | iterador]] que se realiza con un [[Python#Iterable | iterable]], el cual nos devuelve una lista con cada una de las [[Python#Iteration | iteraciones]], por ejemplo, tenemos un string, nos devuelve cada una de los caracters.

<br/>

```jupyter
vec = [1, 2, 3, 4, 5]
vec = 'python'
square = list(map(lambda x: x ** 2, vec))
square
```

La función **map()** recibe dos parámetros:

| función   | parámetro x    | parámetro y |
| --------- | -------------- | ----------- |
| map(x, y) | función lambda | Lista input |

Donde se recomienda usar una [[Python#Lambda| función lambda]] en el iterador **map** donde se le agrega un parámetro el cual es la iteración.

<br/>

---

<br/>

# Filter

Esta es un [[Python#Iterator|iterador]], el cual permite hacer una [[Python#Iteration]] con una condición, si la cumple se almacena el valor.

```jupyter
iter = range(100)
out = list(filter(lambda x: x%2 == 0, iter))
print(out)
```
<br/>

| función      | parámetro x    | parámetro y |
| ------------ | -------------- | ----------- |
| filter(x, y) | función lambda | Lista input |

Donde se recomienda usar una [[Python#Lambda| función lambda]] en el iterador **filter** donde se le agrega un parámetro el cual es la iteración.
