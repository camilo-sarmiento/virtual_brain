
# Unidades de medida

## Bit

La unidad de medida más básica es un bit, el cual es un binario que consta de una variable de 1 o 0.

```asciidoc-table
|===

19+^| Bits

| 0 | 1 | 0 | 1 | 1 | 1 | 1 | 0 | 1 | 1 | 0 | 1 | 1 | 0 | 0 | 0 | 1 
| 1 | 0 

|===
```

<br/>

---

<br/>

## byte

En 1956 **IBM** Diseña un estándar para representar los caracteres, donde establecieron que el conjunto de ocho (8) **bits** forman un **byte**, y a su vez este forma un carácter.

|  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  | 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  0  |  1  |  0  |  0  |  0  |  1  |  1  |  0  |

<br/>

---

<br/>

## ¿Cómo funciona los bytes?

Para poder saber como funciona veremos un ejemplo, donde tenemos un conjunto binario de 8 bits *(01101011)*.

Cuando tenemos un byte de 8 bits empezamos de derecha a izquierda, donde podemos ver que empieza en 1, el siguiente es la suma del numero anterior por si mismo, así sucesivamente hasta tener lo 8 *(1, 2, 4, 8, 16, 128)*.

|  **Index**  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
|:-----------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Binario** |  0  |  1  |  1  |  0  |  1  |  0  |  1  |  1  |
|  **Bits**   | 128 | 64  | 32  | 16  |  8  |  4  |  2  |  1  |



Con la tabla podemos verlo mejor, con el binario *(01101011)* empezamos en el index 1, si el binario es 1 se suma el bit con el siguiente binario 1.

<br/>

![Diagram.svg](Informatica%20y%20redes/src/Diagram.svg)

Podemos ver que con el numero binario *(01101011)* debemos sumar:
```ad-example
title: Info
collapse: open

1 + 2 + 8 + 32 + 64 = 107

```

El número 107 se le asigna a un carácter especifico, en este caso es la letra 'K'.

<br/>

---

### ASCII y UTF-8
Todos los **Bytes** con su carácter se guardaron en la tabla **ASCII**, Con el tiempo se decidió crear un estándar para todos lo caracteres del mundo, donde algunos idiomas manejaban letras o signos distintos como el ruso, chino japones, hispano, etc.

Por esta razón se diseño **UTF-8**, un formato de codificación de caracteres **Unicode** e **ISO 10646** que utiliza símbolos de longitud variable, además de ser compatible con **ASCII**.

![[New_Unicode_logo.svg]]

Más adeleante se actualizo a **UTF-16**, donde se usaba 16 bits, que permitieron agregar muchos más caracteres, como lo &#129327 emojis &#129327.

<br/>

---

<br/>

## Conversión de bytes

Por lo general un **byte** es una unidad muy pequeña, entonces para que se más manejable se utilizan conversiones de medidas como en la física, por ejemplo, *10 Milímetros es un 1 Centímetro, 100 Centímetros son 1 Metro*, etc.

| Medida          | Byte           | Byte                    |
| --------------- | -------------- | ----------------------- |
| 1 Byte          | 8 Bits         | 8 Bits                  |
| 1 Kilobyte (KB) | $2^{10}$ Bytes | 1.024 Bytes             |
| 1 Megabyte (MB) | $2^{20}$ Bytes | 1.048.576 Bytes         |
| 1 Gigabyte (GB) | $2^{30}$ Bytes | 1.073.741.824 Bytes     |
| 1 Terabyte (TB) | $2^{40}$ Bytes | 1.000.000.000.000 Bytes | 
| 1 Petabyte (PB) | $2^{50}$ Bytes | 1.1258999e+15 Bytes     |
| 1 Exabyte (EB)  | $2^{60}$ Bytes | 1.1529215e+18 Bytes     |

<br/>

---

<br/>

## Binary Conversor

Un ejemplo de como funciona la conversión de byte a un código de un carácter. El siguiente programa en [Python](Python.md) muestra como transformar un **byte**.   

```jupyter {python - binary convertion} 
binary = 10110011
bit = [128, 64, 32, 16, 8, 4, 2 ,1]
bit_serie = []
result = 0

for i, bin in enumerate(str(binary)):
    if bin == '1':
        bit_serie.append(bit[i])
        num = bit_serie[-1]
        result += num

print(f'Our binary is {binary},\nwhere is add {bit_serie}\nand the result is {result}')
```

```ad-tip
collapse: open
[[Python]] cuenta con un par de funciones * **ord()** * que permite encontrar el código de un carácter, * **chr()** * que permite encontrar el carácter por medio del código.

```jupyter
print(f'character number 124 is: {chr(124)}, "a" code is: {ord("a")}')

```

