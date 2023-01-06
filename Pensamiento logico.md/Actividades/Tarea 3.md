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
<hr class="subtitle">

Como lo pudimos ver anteriormente, no se cumple la igualdad de la operación:

> 𝐁 ∩ (𝐀 Δ 𝐂) = (𝐁 Δ 𝐂) − 𝐀

Debido a que dan dos resultados completamente diferentes, por ende, debería ser:

> 𝐁 ∩ (𝐀 Δ 𝐂) != (𝐁 Δ 𝐂) − 𝐀

 ![[pasos_B_1-2.svg]]

<br/>
<br/>

# Ejercicio 3: <br/> Operaciones entre conjuntos
Aplicación de la Teoría de Conjuntos

<br/>

## Definición de conjuntos
<hr class="subtitle">

![T_3_B_3.svg](T_3_B_3.svg)

Teniendo en cuenta el conjunto dado, lo podemos expresar mediante **Extensión**, de la siguiente manera:

>**U** = {6, 7, 9, 11, 15, 16, 19, 21}
>
>**A** = {6, 11, 15, 21}
>
>**B** = {6, 7, 11, 16}
>
>**C** = {6, 7, 9, 21}

<br/>

Después resolvemos las siguientes operaciones:
> 1. B U (𝐴 - 𝐶)
> 2. (B ∩ C) Δ A>
> 3. A' - (C - B)
> 4. (𝐴 - C) ∩ B

<br/>

### Operación 1
<hr class="subtitle">

![B_3_1.svg](B_3_1.svg)

Teniendo en cuenta la operación **B U (𝐴 - 𝐶)**, realizamos primero la **diferencia**, y después la **Unión**.

>𝐴 - 𝐶 = {11, 15}
>
>B U (𝐴 - 𝐶) ={6, 7, 11, 15, 16}

---

<br/>

### Operación 2
<hr class="subtitle">

![B_3_2.svg](B_3_2.svg)

Teniendo en cuenta la operación **(B ∩ C) Δ A**, realizamos primero la **intersección**, y después la **diferencia simétrica**.

>B ∩ C = {6, 7}
>
>(B ∩ C) Δ A = {7, 11, 15, 21}

---

<br/>

### Operación 3
<hr class="subtitle">

![B_3_3.svg](B_3_3.svg)

Teniendo en cuenta la operación **A' - (C - B)**, realizamos primero la **Complementación** y la **diferencia**, después se hace la última **diferencia**.


>A' = {7, 9, 16, 19}
>
>(C - B) = {9, 21}
>
>A' - (C - B) = {7, 16, 19}

---

<br/>

### Operación 4
<hr class="subtitle">

![B_3_4.svg](B_3_4.svg)

Teniendo en cuenta la operación **(𝐴 - C) ∩ B**, realizamos primero la **diferencia**, y después se hace la  **intersección**.

>(𝐴 - C) = {11, 15}
>
>(𝐴 - C) ∩ B = {11}

<br/>
<br/>

---

# Ejercicio 4: <br/> Aplicación de la Teoría de Conjuntos
Aplicación de la Teoría de Conjuntos

<br/>

## Situación problémica

La **Universidad Nacional Abierta y a Distancia** organiza las Olimpiadas anuales para sus estudiantes inscritos. En un grupo de **350 estudiantes** seleccionados por sus capacidades y competencias, se determina que:

> - **145** se inscribieron a **tenis de mesa**.
> 
> - **115** se inscribieron en **bolos**.
> 
> - **150** se inscribieron en **fútbol**.
> 
> - **50** se inscribieron **solo a tenis de mesa**.
> 
> - **30** se inscribieron **sólo a bolos**.
> 
> - **45** estudiantes se inscribieron simultáneamente en las **tres modalidades**.
> 
> - **30** estudiantes se inscribieron a **bolos y fútbol**, pero **no a tenis de mesa**.
> 
> - **40** estudiantes se inscribieron a **tenis de mesa y a fútbol**, pero **no a bolos**.

Teniendo en cuenta la información anterior, se contestará:
> 1. ¿Cuántos estudiantes se inscribieron sólo a fútbol?
> 
> 2. ¿Cuántos estudiantes se inscribieron a tenis de mesa y bolos, pero no a fútbol?
> 
> 3. ¿Cuántos estudiantes no se inscribieron a ninguna de las tres modalidades?

<br/>

## Definición de conjuntos



>**U** = {x | x este seleccionado por sus capacidades y competencias}
>**|U|** = 350
>
>**A** = {x | x este inscrito en tenis de mesa}
>**|A|** = 145
>
>**B** = {x | x este inscrito en bolos}
>**|B|** = 115
>
>**C** = {x | x este inscrito en fútbol}
>**|C|** = 150
>
>**D** = {x | x no este inscrito en ninguna modalidad}
>**|D|** = 110

<br/>

### ¿Cuántos estudiantes se inscribieron sólo a fútbol?

![B_4_1.svg](B_4_1.svg)

>**C - (A U B)** = {35}

<br/>

---

### ¿Cuántos estudiantes se inscribieron a tenis de mesa y bolos, pero no a fútbol?

![B_4_2.svg](B_4_2.svg)

>**(A ∩ B) - C** = {10}

<br/>

---

### ¿Cuántos estudiantes no se inscribieron a ninguna de las tres modalidades?

![B_4_3.svg](B_4_3.svg)

>**(A U B U C)'** = {D}