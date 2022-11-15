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

---

## Tabla de verdad

```jupyter
pro = 3
pos = 2

pos ** pro
```

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

Según los resultados de la tabla de verdad, podemos concluir que la afirmación [[Tarea 1#^c5e400 | 𝑝 -> (q ∧ 𝑟)]] es una **Contingencia**.

<br/>
<br/>

# Ejercicio 2: Identificación de las reglas de la inferencia lógica

<hr class="subtitle">

## Ejercicio 1

> * <mark class="hltr-green">**p:**</mark> Carlos sabe como se realiza la potenciación.
<br/>
> * <mark class="hltr-blue">**q:**</mark> Debe estudiar el tema de la multiplicación. 
<br/>

> **{(¬p -> q) ∧ ¬q} ∴ p **

<br/>

### Lenguaje natural


Si <mark class="hltr-green">Carlos sabe como se realiza la potenciación </mark>, entonces <mark class="hltr-blue">para el futuro de la educación es importante que las instituciones busquen nuevos planes</mark> y <mark class="hltr-red">para el futuro de la educación es importante que las instituciones busquen nuevos modelos educativos para recuperar el tiempo perdido durante la pandemia</mark>.

<br/>

---
<br/>

## Ejercicio 2

> * <mark class="hltr-green">**p:**</mark> Carlos quiere estudiar ingeniería civil 
<br/>
> * <mark class="hltr-blue">**q:**</mark> Debe estudiar el tema de la multiplicación. 
<br/>

> **{(¬p -> q) ∧ ¬p} ∴ q **

<br/>

### Lenguaje natural


Si <mark class="hltr-green">Carlos sabe como se realiza la potenciación </mark>, entonces <mark class="hltr-blue">para el futuro de la educación es importante que las instituciones busquen nuevos planes</mark> y <mark class="hltr-red">para el futuro de la educación es importante que las instituciones busquen nuevos modelos educativos para recuperar el tiempo perdido durante la pandemia</mark>.