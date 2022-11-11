# Cuantificadores

Los **cuantificadores** son símbolos que determinan la cantidad de una preposición  categórica. Estos se dividen en 2 principalmente:

* [[Cuantificadores#Cuantificadores Universales| Cuantificadores Universales(∀)]]
* [[Cuantificadores#Cuantificadores Existenciales| Cuatificadores Existenciales(Ǝ)]]


<br/>

---

## Cuantificadores Universales

> Se representa con el símbolo **∀**

Con este podemos referirnos a todos los elementos de un conjunto, donde todos deben cumplir con la sentencia.

<br/>

### Forma afirmativa(∀)

* Para todo...
* Para cada...
* Para cualquier...
<br/>

### Forma negativa(∀¬)

* No es cierto que, para todo...
* No es cierto que, para cada...
* No es cierto que cualquier...
<br/>

### Ejemplos
<hr class="subtitle"/>

#### Forma escrita

Dada la expresión:

> $$ (∀_x \in \mathbb{R}) \space (x + 1 > 1) $$

Se puede leer:

* **Para todo** número x que pertenece a los reales, x mas 1 es mayor que 1
* **Para cualquier** número x que pertenece a los reales, x mas 1 es mayor que 1
* **Para cada** número x que pertenece a los reales, x mas 1 es mayor que 1

<br/>

#### Forma matemática
Dada la expresión:
> $$ f(x) = 2x^3 + 3 > 10 \space  donde \space  x \in  \mathbb{N}$$

Donde la preposición **cuantificada** es:

> $$∀_x \in \mathbb{N}; \space 2x^3 + 3 > 10$$

Se puede leer:

* **Para todo** número x que pertenece a los naturales, 2 por x al cubo mas 3 es mayor que 10
* **Para cualquier** número x que pertenece a los naturales, 2 por x al cubo mas 3 es mayor que 10
* **Para cada** número x que pertenece a los naturales, 2 por x al cubo mas 3 es mayor que 10


```ad-example
Si lo comprobamos la expresión podemos darnos cuenta que es **falso**, por que **no todos los números naturales** en la función son mayores a 10.
```jupyter
x = 1
2 * x**3 + 3 > 10
```



<br/>

<br/>

---

## Cuantificadores Existenciales

> Se representa con el símbolo **Ǝ**

Este nos permite referirnos a uno o varios elementos de un conjunto, en los cuales no todos deben cumplir la sentencia.

<br/>

### Forma afirmativa(Ǝ) 

* Existe algún...
* Algunos...
* Existe por lo menos...

<br/>

### Forma negativa(∄)
* No existe algún...
* No existe un...
* No existe por lo menos...


<br/>

### Ejemplos
<hr class="subtitle"/>

#### Forma escrita

Dada la expresión:

> $$ (\exists x \in \mathbb{Z}) \space (x + 2 = 0) $$

Se puede leer:

* **Existe un** número x que pertenece a los enteros, x mas 2 es igual a 0
* **Para algún** número x que pertenece a los enteros, x mas 2 es igual a 0
* **Al menos para un** número x que pertenece a los enteros, x mas 2 es igual a 0

<br/>

#### Forma matemática
Dada la expresión:
> $$ f(x) = 3^x + 1 = 10 \space  donde \space  \exist x \in  \mathbb{N}$$

Donde la preposición **cuantificada** es:

> $$\exists x \in \mathbb{N}; 3^x + 1 = 10 $$

Se puede leer:

* **Existe un** número x que pertenece a los naturales, 3 elevado a la x mas 1 es igual a 10
* **Para algún** número x que pertenece a los naturales, 3 elevado a la x mas 1 es igual a 10
* **Al menos para un** número x que pertenece a los naturales, 3 elevado a la x mas 1 es igual a 10


```ad-example
Si lo comprobamos la expresión, podemos darnos cuenta que es **verdadero**, por que **alguno de los naturales** en la función es igual a 10.
```jupyter
x = 2
3**x + 1 == 10
```



<br/>

<br/>

---

## Equivalencia entre cuantificadores

Los cuantificadores tienen una equivalencia cuando se hace una preposición.

Por ejemplo, podemos hacer una tabla con todas las **equivalencias** con una preposición, donde tenemos un conjunto de animales y nos referimos si son carnívoros, entonces tenemos:
```ad-summary
Recorndemos que:
∀ se refiere a todos los elementos.
$\exists$ se refiere a solo algunos de los elementos


```

> **x =** Animal
> **p(x) =** de tipo carnívoro

| Fórmula                       | Preposición                        | Equivalencia                        | Preposición de equivalencia           |
| ----------------------------- | ---------------------------------- | ----------------------------------- | ------------------------------------- |
| $$∀_x \space p(x)$$           | Cada **x** es **p(x)**        | $$\nexists_{x} \space  \neg p(x) $$ | No hay algún **x** que no es **p(x)** |
| $$∀_x \space \neg p(x)$$      | Cada **x** no es **p(x)**     | $$\nexists_{x} \space p(x) $$       | No hay algún **x** que es **p(x)**    |
| $$\exists_x \space p(x)$$      | Hay algún **x** que es **p(x)**    | $$\neg ∀_{x} \space \neg p(x) $$    | No todos **x** no son **p(x)**        |
| $$\exists_x \space \neg p(x)$$ | Hay algún **x** que no es **p(x)** | $$\neg ∀_{x} \space p(x) $$         | No todos **x** son **p(x)**           |

<br/>

Esto nos da una idea para saber si **todos** o **algunos** elementos cumplen cierta preposición. 

> En el caso del ejemplo, si todos o algunos **animales** son **de tipo carnívoros**

|    Lógica    | Cantidad                     | Calidad    | Tipo | Forma                   |
|:------------:| ---------------------------- | ---------- | ---- | ----------------------- |
|      ∀       | Universal                    | Afirmativa | A    | Todo **x** es **p**     |
| $$\exists$$  | Existenciales / particulares | Afirmativa | I    | Algún **x** es **p**    |
|  $$\neg ∀$$  | Universal                    | Negativa   | E    | Ningún **x** es **p**   |
| $$\nexists$$ | Existenciales / particulares | Negativa   | O    | Algún **x** no es **p** |

$$∀ \neg(\neg ∀)$$
$$\exists \to \nexists$$

1. Todos los políticos son mentirosos ^9843dc
2. Algún político es mentiros ^794b0a
3. Todos los políticos no son mentirosos ^d55403
4. Algún político no es mentiroso ^b831ed


Si A es verdadera:
![[Cuantificadores#^9843dc]]
O es falsa(contradicción):

![[Cuantificadores#^b831ed]]

I es verdadera (subalterna):
![[Cuantificadores#^794b0a]]

E es falsa (contrariedad):

![[Cuantificadores#^d55403]]
