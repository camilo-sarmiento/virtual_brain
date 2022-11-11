# *args and **Kwargs
<head>
<link rel="stylesheet" href="styleawds.css" />

</head>
Son utilizados para asignarle un número indefinido de argumentos a una función, pero hay que saberlos usar para no generar un caos en el código.

Hay que aclarar que *args y \*\*kwargs se dividen en dos partes:

| Signo | Variable |
| ----- | -------- |
| *     | args     |
| **    | kwargs   |

Donde el **signo** los diferencia y la **variable** puede ser llamada de cualquier manera *(\*argumentos, \*\*argumentos)*, pero **args y kwars** es una convención

<br/>

---

<br/>

## *args

Es usado para pasarle a una función un número indeterminado de argumentos, donde **args** se convierte en una [[Python#Tuplas|Tuplas]] de los elementos que agregamos como argumentos.
``` jupyter
def test_var_args(*args):

	print("Normal args:", args)

	for i, arg in enumerate(args):

		print(f"Arg number {i} using *args: {arg}")

test_var_args('yasoob', 'python', 'eggs', 'test')
```


<br/>

---

<br/>


## **kwargs

Al igual que **\*args**, **\*kwargs** permite darle un número indefinido de argumentos a una función, pero a diferencia del anterior, este dentro de la función se convierte en un [[Python#Diccionarios| Diccionario]], por ende, lo argumentos deben tener una **key** y un **value**.   

``` jupyter
def greet_me(**kwargs):

	print(kwargs)  

	for key, value in kwargs.items():

		print(f"key is {key} = value is {value}")


greet_me(name="yasoob", language = 'Python', city = 'NY', age = 25)
```





