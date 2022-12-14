# Partes de la circunferencia

![[Pensamiento logico.md/src/Diagram.svg]]

> ### Centro:
> Es un punto central, el cual esta equidistante de cualquier punto de la **circunferencia**.

>### Radio:
>Es la distancia que existe entre el **centro** y cualquier otro punto de la **circunferencia.** Por lo general re representa con la letra ***r.***

>### Arco:
>Es una porción de la **circunferencia**, la cual es definida por dos puntos.

>### Cuerda:
>Es un línea entre **dos puntos**, la cual debe estar en el interior de la **circunferencia.**

>### Diámetro:
>Es una line que divide a la **circunferencia** y que atraviesa el centro, además, este equivale al doble del **radio.**

>### Tangente:
>Es una línea que atraviesa un punto de la **circunferencia** que esta en su parte exterior.

>### Secante:
>Es una línea recta que atraviesa a la **circunferencia** y toca dos puntos.

<br/>

---

<br/>

# Ecuación canónica
*De la circunferencia*

> $$(x - h)^2 + (y - k)^2 = r^2$$

<br/>

Donde **h y k** son las **coordenadas del centro** de la circunferencia.

Es la ecuación utilizada para poder encontrar la coordenadas del centro y el radio de una **circunferencia.**

 * **Centro** = (h, k)
 * **radio** = r

* x - y: Deben tener un coeficiente de 1, no puede ser 2x, 3y.

* (x - h), (y - k): Deben estar elevados al cuadrado.

* (x - h) **+** (y - K): Los dos términos deben sumarse.

<br/>

## Ejemplos

<hr class="subtitle"/>

> $$(x - 3)^2 + (y - 2)^2 = 10^2$$

> $$(x + 1)^2 + (y - 7)^2 = 36$$

> $$\left( x - \frac{1}{2} \right)^2 + (y + 5)^2 = 20$$



<br/>

---

<br/>

# Ecuación General
*De la circunferencia*
<br/>

>$$x^2 + y^2 + Dx + Ey + F = 0$$



Si nos dan la ***ecuación*** de una circunferencia, a partir de ella podemos encontrar las coordenadas de su centro y el valor de su radio para graficarla o dibujarla.

Y si nos dan las coordenadas del centro de una circunferencia y el radio o datos para encontrarlo, podemos llegar a la ecuación de la misma circunferencia.

<br/>


* D y E: son los valores de la circunferencia.

* 0: Deben estar igualada a 0.

* F: Es la constante.

* Las variables ***(x, y)*** siempre se suman.

<br/>

## Ejemplos

<hr class="subtitle"/>

> $$x^2 + y^2 + 2x + 5y + 10 = 0$$

> $$x^2 + y^2 + \frac{1}{5}x + y + 10 = 0$$

> $$x^2 + y^2 + 2x + \sqrt{ 5 }y + 10 = 0$$


<br/>

---

<br/>

# Ecuación Canónica a General


> $$(x - h)^2 + (y - k)^2 = r^2$$

<br/>

Remplazamos los valores de *(h, k, r)* 

1. > $$(x + 21)^2 + (y - 5)^2 = 36^2$$

<br/>

Realizamos el [[binomio cuadrado perfecto]] de los dos términos.

2. > $$x^2 + 2(x)(21) + 21^2 + y^2 - 2(y)(5) + 5^2 = 1296$$

<br/>

Realizamos las operaciones.

3. > $$x^2 + 42x + 441 + y^2 - 10y + 25 = 1296$$

<br/>

Igualamos a *0*, donde cambiamos la igualdad *(1296)* al otro lado con el **signo opuesto**.

4. > $$x^2 + 42x + 441 + y^2 - 10y + 25 - 1296 = 0$$

<br/>

Ordenamos la ecuación según la ecuación general.

5. > $$x^2 + y^2 + 42x - 10y - 830 = 0$$

<br/>

>$$x^2 + y^2 + Dx + Ey + F = 0$$


<br/>

---

<br/>

# Ecuación General a Canónica



>$$x^2 + y^2 + Dx + Ey + F = 0$$

<br/>

Remplazamos los valores de *(D, E, F)* 

1. > $$x^2 + y^2 - 14x - 69y - 17 = 0$$

<br/>

Ordenamos la ecuación según la variable ***(x, y)***.

2. > $$x^2 - 14x + y^2 - 69y - 17 = 0$$

<br/>

Completamos el [[Trinomio cuadrado perfecto]], donde tomamos el coeficientes de las variables **(x, y)**, dividimos cada una en 2 y los elevamos al cuadrado, de esta manera: 

$$14x = \left(\frac{15}{2}\right)^2 = 49$$ 
$$69y = \left(\frac{69}{2}\right)^2 = 1190$$ ^b509e1

3. > $$x^2 - 14x + 49 + y^2 - 69y + 1190 - 17 = 0$$

<br/>

Realizamos el cambio de la constante **(17)** después de la igualdad con **signo opuesto** y además  agregando las operaciones del [[circunferencia#^b509e1|trinomio cuadrado perfecto]] para conservar la igualdad la igualdad

4. > $$x^2 + 14x + 49 + y^2 - 69y + 1190 = 17 + 49 + 1190$$

<br/>

Realizamos la factorización de [[Trinomio cuadrado perfecto]], donde se le saca raíz cuadrada a las variables **(x, y)** elevadas al cuadrado, y a las operaciones del [[circunferencia#^b509e1|trinomios cuadrado perfecto]] de la siguiente manera:

$$\sqrt{x^2} = x$$
$$\sqrt{49} = 7$$
$$\sqrt{y^2} = y$$
$$\sqrt{1190} = 34.5$$

Lo que nos da como resultado un [[binomio cuadrado perfecto]]

5. > $$(x - 7)^2 + (y - 34.5)^2 = 1190$$

<br/>

> $$(x - h)^2 + (y - k)^2 = r^2$$



<br/>

---

<br/>

# Hallar el centro

Si tenemos una ecuación general, con esta podemos encontrar el **centro** de la circunferencia con la siguiente operación.

>$$x^2 + y^2 + Dx + Ey + F = 0$$

>$$\left(\frac{-D}{2}, \frac{-E}{2}\right)$$


Por ejemplo, tenemos esta ecuación.

1. > $$x^2 + y^2 - \frac{32}{3}x - \sqrt{25}y - 101 = 0$$

<br/>

Primero resolvemos los valores.

2. > $$x^2 + y^2 - 10.66x - 5y - 101 = 0$$

<br/>

Remplazamos los valores.

3. > $$\left(\frac{-(-10)}{2}, \frac{-(-5)}{2}\right)$$

<br/>

Resolvemos los signos ***(- \* - = +)***.

4. > $$\left(\frac{10}{2}, \frac{5}{2}\right)$$

<br/>

Por último, resolvemos las operaciones.

5. > $$(5, 2.5)$$


<br/>

---

<br/>

# Hallar el radio

Si tenemos una ecuación general, con esta podemos encontrar el **radio** de la circunferencia con la siguiente operación.

>$$x^2 + y^2 + Dx + Ey + F = 0$$

>$$r = \frac{1}{2} \sqrt{D^2 + E^2 - 4F}$$


Por ejemplo, tenemos esta ecuación.

1. > $$x^2 + y^2 - \sqrt{54}x - 284y - 69 = 0$$

<br/>

Remplazamos los valores.

2. > $$r = \frac{1}{2} \sqrt{\sqrt{54}^2 + 284^2 - (4)(69)}$$

<br/>

Primero resolvemos los valores.

3. > $$r = \frac{1}{2} \sqrt{7.3^2 + 284^2 - (4)(69)}$$

<br/>

Resolvemos las operaciones.

4. > $$r = \frac{1}{2} \sqrt{53.29 + 80656 - 276}$$

<br/>

Resolvemos la operación de la raíz.

5. > $$r = \frac{1}{2} \sqrt{80433.29}$$

<br/>

Resolvemos la raíz cuadrada.

6. > $$r = \frac{1}{2} (283)$$

<br/>

Resolvemos los multiplicación

7. > $$r = \frac{1}{2} * \frac{283}{1} $$

Por último, resolvemos las operaciones.

8. > $$r = \frac{283}{2} = 141.5$$


# Elipse

![[Pasted image 20221117151223.png]]

## ecuaciones
![[Pasted image 20221117152052.png]]

![[Pasted image 20221117153335.png]]