![[Pasted image 20221108191631.png]]

# Proposición simple
> preposición simplo o atomica

no usa cnectores

# proposición molecular

>molecular molecular o compuesta

son varias preposiciones unidas con conectores logicos

# Conectores lógicos
![[Pasted image 20221108192222.png]]
| conectores | significado | proposición compuesta | nombre |
| ---------- | ----------- | --------------------- | ------ |
| ^          | and         | p ^ q                 |        |

# Tabla de verdad

## Not
| p   | $$ \neg p$$ |
| --- | ----------- |
| V   | F           |
| F   | V           |

p = el gato está feliz
$$\neg p$$ = el gato **no** está feliz

## And
es verdadero cuando las dos preposiciones *(p, q)* son verdaderas.

| p   | q   | p ^ q |
| --- | --- | ----- |
| V   | V   | V     |
| V   | F   | F     |
| F   | V   | F     |
| F   | F   | F     |

```ad-example
para saber el numero de filas
las posibilidades elevado al numero de preposiciones

```

## Condicional

Es verdaero cuando alguna es verdaera

| p   | q   | p -> q |
| --- | --- | ------ |
| V   | V   | V      |
| V   | F   | F      |
| F   | V   | V      | 
| F   | F   | V      |

## Condicional


| p   | q   | p -> q |
| --- | --- | ------ |
| V   | V   | V      |
| V   | F   | F      |
| F   | V   | V      |

> **Tautología** es cuando una tabla tiene todos los resultados en verdadero
> **Contradicción o absurda** es cuando una tabla tiene todos los resultados son falsos
> Contingencia es cuando uno solo queda verdadero o falso y los demás son opuestos.
![[Pasted image 20221108194049.png]]
| p   | q   | r   | $$\neg r$$ | p -> q | q -> r | (p -> r) 
| --- | --- | --- | ---------- | ------ | ------ |
| --- |     |     |            |        |        |


# ejercicio 1
p = coronavirus se originó en china
q = el coronavirus es mortal
r = algunos han muerto por covid
[(p^r ) v (p -> q)]

lenguaje natural:
el covid se originó en china y han muerto. o si el covid se origino en china, entoces es mortal

