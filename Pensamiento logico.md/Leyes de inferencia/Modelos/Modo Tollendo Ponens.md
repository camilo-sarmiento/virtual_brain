## **Modo Tollendo Ponens**
<p style="font-size: 15px"> (MTT)</p>

> *Negando o Niego*

En este modo implica una comparación entre dos preposiciones, donde la conclusión tendremos el termino positivo, esto quiere decir que por lo menos debe haber un termino positivo para que la preposición se cumpla.

*parecido al **or** *

---

* **x =** Realizo la tarea \
* **y =** Voy a la fiesta

| Premisas  | Conclusión |
| --------- | ---------- |
| x *v* y   | y, y       |
| ¬x *v* y  | y          |
| x *v* ¬y  | x          | 
| ¬x *v* ¬y | *False*    |

> Si x or no y, entonces x. 
> Si No x or y , entonces x.
> Si No x or No y, entones no se cumple la sentencia.

---

```py
x = True
y = None

if x:
    print('x es afirmativo, entonces y es negativo')

else:
    y = False
    print('x es negativo, entonces y es positivo')
```
