# Ejercicio 1: <br/> Determinación y clases de conjuntos
Aplicación de la Teoría de Conjuntos

<br/>

> **B** = {x | x $\in \mathbb{Z}$, x es impar ∧ -10 <= x}
> or
> **B** = {x | x $\in \mathbb{Z}$, x % 2 != 0 ∧ -10 <= x}

Sea **B** el conjunto conformado por toda **x**, tal que, x pertenece a los números enteros, **x** es impar y **x** es mayor o igual a **-10**.

Para dar respuesta a los ítems, debemos tener encuentra las características de **B**:

- **x** pertenece a los números Enteros $\mathbb{Z}$, por ende **x** está entre ($-\infty$, $\infty$)
- **x** % 2 != 0, por ende **x** debe ser **impar**.
- **-10 <= x**, por ende **x** está entre (-10, $\infty$)

<br/>

## Extensión
<hr class="subtitle">
Teniendo encuentra las características de **B**, podemos de decir que **x** esta entre (-9, $\infty$), siendo **x** un numero impar.

>**B** = {-9, -7, -5, -3, -1, 1, 3, 5, 7, 9, 11, 13, ...}

<br/>

## Tipo de conjunto
<hr class="subtitle">
Teniendo encuentra las características de **B**, podemos de decir que **x** solo debe ser mayor o igual a **-10**, lo que significa que es un:

> Conjunto infinito

<br/>

## cardinalidad
<hr class="subtitle">
Teniendo encuentra las características de **B**, podemos de decir que **B** tiene infinitos elementos.

>**|B|** = $\infty$

<br/>
<br/>

---

# Ejercicio 2: <br/> Representación de conjuntos
Aplicación de la Teoría de Conjuntos

<br/>

## Definición de conjuntos
<hr class="subtitle">

>**U** = Alumnos que realizarán la excursión del fondo marino
>**U** = {x | x que realizarán la excursión del fondo marino}

>**A** = Alumnos que tienen un promedio mayor o igual a 4.5
>**A** = {x | x tiene un promedio >= 4.5}

>**B** = Alumnos que pertenezcan al programa de biología marina
>**B** = {x | x pertenece al programa de biología marina}

>**C** = Alumnos que sean mujeres y que sean mayores de 25 años
>**C** = {x | x es mujer ∧ x > 25 años}

<br/>

## Comprobación de la igualdad
<hr class="subtitle">

Después tener los conjuntos definidos, debemos comprobar que si la siguiente operación es una verdadera igualdad:

> 𝐁 ∩ (𝐀 Δ 𝐂) = (𝐁 Δ 𝐂) − 𝐀

Para ello debemos realizar cada uno de los términos, y así poder dar una conclusión.

<br/>

### Primer término
<hr class="subtitle">
> 𝐁 ∩ (𝐀 Δ 𝐂)

El primer término nos dice que es la **Intersección** entre **B** y la **Diferencia Simétrica** entre **A** y **C**.

Para ello realizamos la operación que está entre paréntesis (𝐀 Δ 𝐂), y después hacemos la **intersección**

![[pasos_B_2.svg]]

Por ende, este término es igual a:

los alumnos que pertenezcan al programa de bilogía marina **y** que tengan un promedio mayor o igual a 4.5 **y** que **no** sean mujeres mayores de 25 años; **o** los Alumnos que **no** tengan un promedio mayor o igual a 4.5 **y** que sean mujeres mayores de 25 años.

>𝐁 ∩ (𝐀 Δ 𝐂) = {x | x $\in$ B $\land$ ((x $\in$ A $\land$ x $\notin$ C) $\lor$ (x $\notin$ A $\land$ x $\in$ C))}

<br/>

### segundo término
<hr class="subtitle">
> (𝐁 Δ 𝐂) − 𝐀

El segundo término nos dice que es la **Diferencia** entre la **Diferencia Simétrica** entre **A** con **C**, y **A**.

Para ello realizamos la operación que está entre paréntesis (𝐁 Δ 𝐂), y después hacemos la **Diferencia**

![[pasos_B_1.svg]]

Por ende, este término es igual a:

los alumnos que **no** tengan un promedio mayor o igual a 4.5 **y** que **no** pertenezcan al programa de bilogía marina **o** que **no** sean mujeres mayores de 25 años.

>(𝐁 Δ 𝐂) − 𝐀 = {x | x $\notin$ A $\land$ (x $\notin$ B $\lor$ x $\notin$ C)}

<br/>

### Conclusión

Como lo pudimos ver anteriormente, no se cumple la igualdad de la operación:

> 𝐁 ∩ (𝐀 Δ 𝐂) = (𝐁 Δ 𝐂) − 𝐀

Debido a que dan dos resultados completamente diferentes, por ende, debería ser:

> 𝐁 ∩ (𝐀 Δ 𝐂) != (𝐁 Δ 𝐂) − 𝐀

 ![[pasos_B_1-2.svg]]