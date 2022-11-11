## **Silogismo Hipotético**
<p style="font-size: 15px"> (SH)</p>


En este modo implica una serie de condicionales, donde el antecedente será el consecuente de la próxima condición, si todas las condiciones se cumple, obligatoriamente el primer antecedente y el ultimo consecuente serán afirmativos.

---

* **a =** Hoy hace buen tiempo 
* **x =** salgo de mi casa 
* **y =** Jugamos futbol
* **z =** Nos ejercitamos

<br>

|Premisa 1|Premisa 2|Premisa 3|Conclusión|
|--------|---------|---------|----------|
|a -> x  |x -> y   |y -> z   |a -> z    |

 <br>

> Si a, entonces x. \
> Si x, entonces y. \
> Si y, entonces z. \
> Por lo tanto, Si a, entonces z

---

```py
x = True
y = True
z = False

if x and y:
    if y and z:
        print('Entonces x & z se cumplen')
    elif not z:
        print('z no se cumple')
elif not x:
    print('x no se cumplen')
else:
    print('y no se cumple')
```