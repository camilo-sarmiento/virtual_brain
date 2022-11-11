## **Modo Ponendo Ponens**
<p style="font-size: 15px"> (MPP)</p>

> *afirmando - afirmo*

En este modo implica una condición o implicación, establece una relación de causa y efecto entre dos preposiciones.

Establece que si el antecedente *(primer término)* es afirmativo, entonces el consecuente *(segundo término)* es afirmativo

---

* **x =** La economía es dinámica \
* **y =** Se genera empleo

| Premisas | Conclusión |
| -------- | ---------- |
| x -> y   | y          |
| ¬x -> y  | ¬y         |

> Si x, entonces y. \
> Si No x, entonces No y


---

```jupyter
x = True
y = None

if x:
    y = True
    print('x es afirmativo, entonces y es afirmativo')


if not x:
    y = False
    print('y es negativo, entonces x es negativo')
```
