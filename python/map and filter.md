# Map

Este es un [[Python#Iterator | iterador]] que se realiza con un [[Python#Iterable | iterable]], el cual nos devuelve una lista con cada una de las [[Python#Iteration | iteraciones]], por ejemplo, tenemos un string, nos devuelve cada una de los caracters.

<br/>

```jupyter
vec = [1, 2, 3, 4, 5]
vec = 'python'
square = list(map(lambda x: x, vec))
square
```

La función **map()** recibe dos parámetros:

| función   | parámetro x          | parámetro y |
| --------- | -------------------- | ----------- |
| map(x, y) | función para aplicar | Lista input | 

Donde se recomienda usar una [[Python#Lambda| función lambda]] para aplicar como parámetro x


---
contexto 
mallas dentro de cada facultad > asignatura
.

362 x 203.617