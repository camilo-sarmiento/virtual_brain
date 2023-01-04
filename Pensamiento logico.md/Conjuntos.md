
<br/>

# Conceptos
<hr class="subtitle"/>

## Comprensión
Se utiliza simbología matemática para expresar el contenido del conjunto.

>**A** = {x | x $\in \mathbb{N}$; x < 10}

También se puede literalmente, pero se aconseja solo cuando no hay opción

>**A** = {x son los números naturales menores a 10}

<br/>

## Extensión 
Se utiliza para expresar cada uno de los elementos de un conjunto.

>**A** = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}

<br/>

## Cardinalidad
Busca establecer si un conjuntos es:

- Infinito
- Finito y cuantos elementos tiene
- Unitario
- Vacío

<br/>
<br/>

---

# Clases de conjuntos

<br/>

## Conjunto finito
<hr class="subtitle"/>

Es un tipo de de conjuntos donde está constituido por un **rango limitado de elementos**.

> Sea **A** el conjunto formado por **manzanas**
> **A** = {manzana 1, manzana 2, manzana 3}

<br/>

## Conjunto Infinito
<hr class="subtitle"/>
Es un tipo de conjuntos el cual está compuesto por un **rango infinito de elementos**.

> Sea $\mathbb{N}$ el conjunto formado por los **números naturales**
> $\mathbb{N}$ = {1, 2, 3, 4, 5, 6, 7, 8, 9, ...}

<br/>

## Conjunto Unitario
<hr class="subtitle"/>

Es un tipo de conjunto el cual está formado por **un solo elemento**.

> Sea **W** el conjunto formado por el elemento **x**
> **W** = {x}

<br/>

## Conjunto Vacío
<hr class="subtitle"/>

Es un tipo de conjunto el cual está formado por **ningún elemento**.

>Sea **B** el conjunto formado por personas vivas y mayores de 1000 años
>**B** = {}
>*or* 
>**B** = $\emptyset$

<br/>

## Conjunto Universal
<hr class="subtitle"/>

Es un tipo de conjunto el cual está formado por **los demás conjuntos**, además se denota con la letra **U**.

>Se **U** el conjunto de formado por los números reales
>**U** = {$\mathbb{Z}$, $\mathbb{Q}$, $\mathbb{I}$, $\mathbb{N}$}

<br/>

## Conjunto Disyunto
<hr class="subtitle"/>

Son dos o más conjuntos que su elementos **no tiene nada en común**, excepto su conjunto universal.

>Sea **U** el conjunto formado por los números naturales, Donde **A** son los números pares y **B** los números impares.
>**A** = {x | x % 2 = 0}
>**B** = {x | x % 2 != 0}
>**U** = {**A**, **B**}

![[Disyuntos.svg]]

Donde podemos decir que la intersección de los conjuntos **A** y **B** es un **conjunto vacío**.
>**A** $\cap$ **B** = $\emptyset$


<br/>

## Intersección de conjuntos
<hr class="subtitle"/>

Son dos o más conjuntos que al contrario de los disjuntos, estos si tienen elementos en comunes y se representan con el signo $\cap$.

> Sea **A** el conjunto de la cantidad de hombres en las oficina y **B** la cantidad de mujeres.
> **A** = {5, 10, 20, 80, 2}
> **B** = {50, 84, 2, 10, 5}

![[intersección.svg]]

Donde podemos decir que la intersección de los conjuntos **A** y **B** son los elementos en común.

>**A** $\cap$ **B** = {2, 10, 5}

<br/>

## Diferencia de conjuntos
<hr class="subtitle"/>

Son los elementos de un conjunto que **no hacen parte de otro**.

>Sea **A** el conjunto de números naturales menores a 10 
>Sea **B** el conjunto de números múltiplos de 3 y menores a 10
>**A** = {x | x $\in \mathbb{N}$; x < 10}
>**B** = {x | x % 3 = 0}

![[diferencia.svg]]

Donde podemos decir que la diferencia de los conjuntos de **A** y **B** son los elementos que pertenecen a **A**, pero no a **B**.

>**A** - **B** = {x | x $\in$ **A**; x $\notin$ **B**}

<br/>

## Conjunto potencia
<hr class="subtitle"/>

Es aquel que tiene **subconjuntos de si mismo**, donde podemos encontrarlos elevando 2 al numero de elementos.

>**A** ={1, 2, 3}
>$2^3 = 8$
>**P(A)** = {$\emptyset$, {1}, {2}, {3}, {1, 2}, {2, 3}, {1, 2, 3}}

Donde podemos ver que el conjunto **P** elevado a la potencia de **A**, donde se compone de todas la posibles combinaciones de subconjuntos de **A**.

<br/>

## Subconjunto o Contenencia
<hr class="subtitle"/>

Es el conjunto que pertenece a otro, este se representa con el signo $\subset$.

>**A** = {x | x % 2 != 0}
>**B** = {5, 105, 49, 167, 89, 69}

![[Contenencia.svg]]

Donde podemos ver que el conjunto **A** que se compone de lo números impares, y el conjunto **B** se compone de algunos números impares, por ende, todos los elementos de **B** están en **A**

<br/>

### Tipos de Subconjuntos o Contenencias

| Nombre        | Símbolo     | Descripción                                                                                                                                                     |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Subconjunto   | $\subseteq$ | Indica que todos los elementos del conjunto **A** también **pertenecen** al conjunto **B**, y además **A** y **B** tienen el **mismo número de elementos**.     |
| Subconjunto   | $\subset$   | Indica que todos los elementos del conjunto **A** también **pertenecen** al conjunto **B**, pero que puede haber elementos en **B** que no pertenezcan a **A**. |
| Superconjunto | $\supseteq$ | Indica que todos los elementos del conjunto **B** también **pertenecen** al conjunto **A**, y además **A** y **B** tienen el **mismo número de elementos**.     |
| Superconjunto | $\supset$   | Indica que todos los elementos del conjunto **B** también **pertenecen** al conjunto **A**, pero que puede haber elementos en **A** que no pertenezcan a **B**.                                                                                                                                                                |

<br/>

#### Ejemplos

| Símbolo     | Definición                                 | ejemplo                                                                        |
| ----------- | ------------------------------------------ | ------------------------------------------------------------------------------ |
| $\subseteq$ | **A** es subconjunto con igualdad de **B** | **A** = {1, 2, 3} <br/>**B** = {1, 2, 3} <br/>**A** $\subseteq$ **B**          |
| $\subset$   | **A** es subconjunto de **B**              | **A** = {1, 2, 3} <br/>**B** = {1, 2, 3, 4, 5, 6} <br/> **A** $\subset$ **B**  |
| $\supseteq$ | **B** es subconjunto con igualdad de **A** | **A** = {1, 2, 3} <br/>**B** = {1, 2, 3} <br/>**A** $\supseteq$ **B**          |
| $\supset$   | **B** es subconjunto con igualdad de **A** | **A** = {1, 2, 3, 4, 5, 6} <br/>**B** = {1, 2, 3} <br/>**A** $\supseteq$ **B** | 


<br/>
<br/>

---
# Operaciones entre conjuntos

## Unión

Consta de la unión de dos conjuntos en un conjunto universal. Además es importante tener en cuenta que, al hacer la unión de dos conjuntos, no se deben incluir elementos repetidos.

>**A** = {1, 6, 8, 9, 11}
>**B** = {1, 54, 8, 32, 24}
>**C** = {2, 9, 54, 24, 6, 8}
>
>**A** $\cup$ **B** $\cup$ **C** = {1, 2, 6, 8, 9, 11, 24, 32, 54}
>
>**U** = {**A** $\cup$ **B** $\cup$ **C**}

![[Unión.svg]]