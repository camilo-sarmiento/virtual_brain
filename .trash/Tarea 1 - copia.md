# Ejercicio 1: <br/> Proposiciones y tablas de verdad

<hr class="subtitle">

> * <mark class="hltr-green">**p:**</mark> El futuro de la educación aún es incierto
<br/>
> * <mark class="hltr-blue">**q:**</mark> Para el futuro de la educación es importante que las instituciones busquen nuevos planes 
<br/>
> * <mark class="hltr-red">**r:**</mark> Para el futuro de la educación es importante que las instituciones busquen nuevos modelos educativos para recuperar el tiempo perdido durante la pandemia

>* **𝑝 -> (q ∧ 𝑟)** 

^c5e400

<br/>


## Lenguaje natural
Si <mark class="hltr-green">el futuro de la educación  aún es incierto</mark>, entonces <mark class="hltr-blue">para el futuro de la educación es importante que las instituciones busquen nuevos planes</mark> y <mark class="hltr-red">para el futuro de la educación es importante que las instituciones busquen nuevos modelos educativos para recuperar el tiempo perdido durante la pandemia</mark>.

<br/>

### Redacción
Si el futuro de la educación aún es incierto, entonces es importante que las instituciones busquen nuevos planes y nuevos modelos educativos para recuperar el tiempo perdido durante la pandemia.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

---

## Tabla de verdad

<!--
```jupyter
pro = 3
pos = 2

pos ** pro
```-->

<br/>

| p   | q   | r   | q ∧ r | p -> (q ∧ r) |
| --- | --- | --- | ----- | ------------ |
| V   | V   | V   | V     | V            |
| V   | V   | F   | F     | F            |
| V   | F   | V   | F     | F            |
| V   | F   | F   | F     | F            |
| F   | V   | V   | V     | V            |
| F   | V   | F   | F     | V            |
| F   | F   | V   | F     | V            |
| F   | F   | F   | F     | V            | 
<p class="cite">Creación propia</p>

<br/>

![[jtable_act_4_01.png]]
<p class="cite"> Creación en el simulador lógica **UNAD </p>

Según los resultados de la tabla de verdad, podemos concluir que la afirmación [[Tarea 1#^c5e400 | 𝑝 -> (q ∧ 𝑟)]] es una **Contingencia**.

<br/>
<br/>
<br/>
<br/>
<br/>

# Ejercicio 2: Identificación de las reglas de la inferencia lógica

<hr class="subtitle">

## Ejercicio 2.1

> * <mark class="hltr-green">**p:**</mark> Carlos sabe como se realiza la potenciación.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Carlos perdió el examen de multiplicación y potenciación. 
<br/>

> **¬p -> q
> ¬q** 
> <hr class='line-math'> 
> 
>**∴ p **

<br/>

### Lenguaje natural


Si <mark class="hltr-green">Carlos no sabe como se realiza la potenciación</mark>, entonces, <mark class="hltr-blue">Carlos perdió el examen de multiplicación y potenciación</mark>.

<mark class="hltr-blue">Carlos no perdió el examen de multiplicación y potenciación</mark>, por consiguiente, <mark class="hltr-green">Carlos sabe como se realiza la potenciación</mark>.

<br/>

> ### Leyes de inferencia
>[[Leyes de inferencia#Modo Tollendo Tollens|Modus Tollendo Tollens]]

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

---
<br/>

## Ejercicio 2.2

> * <mark class="hltr-green">**p:**</mark> Carlos va a estudiar ingeniería civil.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Carlos va a estudiar música.
<br/>

> **¬p -> q
> ¬p**
> <hr class='line-math'> 
> 
> **  ∴ q **

<br/>

### Lenguaje natural

Si <mark class="hltr-green">Carlos no va a estudiar ingeniería civil</mark>, entonces <mark class="hltr-blue">Carlos va a estudiar música</mark>.

<mark class="hltr-green">Carlos no va a estudiar ingeniería civil</mark>, por consiguiente, <mark class="hltr-blue">Carlos va a estudiar música</mark>.

<br/>

> ### Leyes de inferencia
>[[Leyes de inferencia#Modo Ponendo Ponens|Modus Ponendo Ponens]]


<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

---
<br/>

## Ejercicio 2.3

> * <mark class="hltr-green">**p:**</mark> La fecha para la entrega de proyecto grupal de arquitectura es la otra semana.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Carlos debe darse prisa para terminar el proyecto.
<br/>
> * <mark class="hltr-red">**s:**</mark> Carlos pude hacer el proyecto con Sofía.


> **q -> s
> p -> q **
> <hr class='line-math'>
>
> ** ∴ p -> s **

<br/>

### Lenguaje natural

Si <mark class="hltr-green">Carlos debe darse prisa para terminar el proyecto</mark>, entonces, <mark class="hltr-red">Carlos puede hacer el proyecto con Sofía</mark>.

Si <mark class="hltr-green">la fecha para la entrega del proyecto grupal de arquitectura es la otra semana</mark>, entonces, <mark class="hltr-blue">Carlos debe darse prisa para terminar el proyecto</mark>.

Por consiguiente, si <mark class="hltr-blue">la fecha para la entrega del proyecto grupal de arquitectura es la otra semana</mark>, entonces, <mark class="hltr-red">Carlos puede hacer el proyecto con Sofía</mark>.

<br/>

> ### Leyes de inferencia
>[[Leyes de inferencia#Silogismo Hipotetico|Silogismo Hipotético]]

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

# Ejercicio 3: Aplicación de las reglas de la inferencia lógica

<hr class="subtitle">

Si un Administrador de empresas liderara organizaciones que contribuyen a la construcción del progreso económico, entonces un administrador de empresas ayuda a la economía de un país. Un administrador de empresas no ayuda en la economía de un país.

> * <mark class="hltr-green">**p:**</mark> Un Administrador de empresas liderara organizaciones que contribuyen a la construcción del progreso económico.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Un administrador de empresas ayuda a la economía de un país.

<br/>

### conclusión

Usamos la ley de [[Leyes de inferencia#Modo Tollendo Tollens|Modus Tollendo Tollens (MTT)]], Donde realizamos una implicación entre **p** y **¬q**, la cual nos dice que al negar el consecuente, **automáticamente** se niega el **antecedente**.

> **p -> q
> ¬q **
> <hr class='line-math'>
>
> ** ∴ ¬p**

<br/>

Donde podemos concluir que el resultado de la expresión es **¬p**

> Un Administrador de empresas **no** liderara organizaciones que contribuyen a la construcción del progreso económico

<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

# Ejercicio 4: <br/>Problemas de aplicación

<hr class="subtitle">

## Definiciones

<br/>

### Lenguaje natural
Si <mark class="hltr-green">Carlos estudió para el examen de cálculo toda la noche</mark>, entonces, <mark class="hltr-blue">Carlos está cansado todo el día</mark> y <mark class="hltr-green">Carlos estudió para el examen de cálculo toda la noche</mark> o <mark class="hltr-red">Carlos durmió un par de horas durante la noche</mark> y <mark class="hltr-red">Carlos **no** durmió un par de horas durante la noche</mark>, entonces, <mark class="hltr-blue">Carlos está cansado todo el día</mark>.

Si Carlos estudió para el examen de cálculo toda la noche, entonces, él está cansado todo el día y Carlos estudió para el examen de cálculo toda la noche o durmió un par de horas y Carlos **no** durmió un par de horas durante la noche, entonces, Carlos está cansado todo el día.

<br/>

### Proposiciones simples

> * <mark class="hltr-green">**p:**</mark> Carlos estudió para el examen de cálculo toda la noche.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Carlos está cansado todo el día.
<br/>
> * <mark class="hltr-red">**s:**</mark> Carlos durmió un par de horas durante la noche.

<br/>

## Expresión simbólica

> **[(p -> q) ∧ (p ∨ r) ∧ (¬r)] -> q**

^16ee33

> **p -> q
> p ∨ r 
> ¬r**
> <hr class='line-math'>
>
> ** ∴ q**


<br/>

---

## Tabla de verdad

<br/>

| p   | q   | r   | p -> q | p ∨ r | ¬r  | (p -> q) ∧ (p ∨ r) | {(p -> q) ∧ (p ∨ r)} ∧ (¬r) | [(p -> q) ∧ (p ∨ r) ∧ (¬r)] -> q |
| --- | --- | --- | ------ | ----- | --- | ------------------ | --------------------------- | -------------------------------- |
| V   | V   | V   | V      | V     | F   | V                  | F                           | V                                |
| V   | V   | F   | V      | V     | V   | V                  | V                           | V                                |
| V   | F   | V   | F      | V     | F   | F                  | F                           | V                                |
| V   | F   | F   | F      | V     | V   | F                  | F                           | V                                |
| F   | V   | V   | V      | V     | F   | V                  | F                           | V                                |
| F   | V   | F   | V      | F     | V   | F                  | F                           | V                                |
| F   | F   | V   | V      | V     | F   | V                  | F                           | V                                |
| F   | F   | F   | V      | F     | V   | F                  | F                           | V                                |
<p class="cite">Creación propia</p>

<br/>

![[Jtable_act_4.png]]
<p class="cite">
Creación en el simulador lógica **UNAD**
</p>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

---

## validez de los argumentos

| Premisa 1 | Premisa 2 | Premisa 3 | Conclusión ∴ | 
| --------- | --------- | --------- | ------------ |
| p -> q    | p ∨ r     | ¬r        | q            |


### Premisa 4  

[[Leyes de inferencia#Modo Tollendo Ponens | Modus Tollendo Ponens (MTP)]], Donde se realiza una disyunción inclusiva entre la **premisa 2** y la **premisa 3**.

>**p ∨ r**
>**¬r**
> <hr class='line-math'>
>
>**∴ p**

Donde se concluye que entre **p** o **¬r**, entonces **p**.
<br/>

### Premisa 5 
[[Leyes de inferencia#Modo Ponendo Ponens | Modus Ponendo Ponens (MPP)]], Donde se realiza una implicación entre la **premisa 1** y la **premisa 4**.

>**p -> q**
>**p**
> <hr class='line-math'>
>
>**∴ q**

Donde se concluye que si **p**, entonces **q**, confirmando la validez de la expresión **[(p -> q) ∧ (p ∨ r) ∧ (¬r)] -> q**.

| p   | q   | r   | p ->q | ¬r  | p <->q ->¬r |
| --- | --- | --- | ----- | --- | ----------- |
| v   | v   | v   | v     | f   | f           |
| v   | v   | f   | v     | v   | v           |
| v   | f   | v   | f     | f   | v           |
| v   | f   | f   | f     | v   | f           |
| f   | v   | v   | v     | f   | f           |
| f   | v   | f   | v     | v   | v           |
| f   | f   | v   | v     | f   | f           |
| f   | f   | f   | v     | v   | v           | 

p1 = x v y
p2 = y -> ¬z
p3 = z
p4 =x -> p

p5 = ¬y(MTT 3 - 2)
p6 = x(MTP 5 - 1)

---

∴ p7 = p(MPP 6 - 4)

simplifiación ¬p y ¬r
p v ¬r