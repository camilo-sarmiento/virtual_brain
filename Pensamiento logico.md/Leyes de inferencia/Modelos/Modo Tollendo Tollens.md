## **Modus Tollendo Tollens**
<p style="font-size: 15px"> (MTT)</p>

> *Negando o niego*

En este modo implica en una condición al negar el consecuente, necesariamente se niega el antecedente, esto significa que el resultado de la condición es falso, entonces la condición no se cumplió.

<br>

---

<br>
* **x =** La economía es dinámica \
* **y =** Se genera empleo


|Premisas |Conclusión|
|---------|----------|
| x -> ¬y |¬x, ¬y    |

> Si No y, entonces No x

---

```py
x = False
y = None

if x:
    y = True
    print('y es positivo, x es positivo')
else:
    y = False
    print('y es negativo, x es negativo')