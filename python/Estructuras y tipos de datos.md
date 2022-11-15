# Estructuras de datos
<br/>

## Pila
<hr class="subtitle"/>
> **primero en ENTRAR, último en SALIR**

_¿Alguna vez usó un **botón de retroceso** en su **navegador** ? 

Abre **facebook.com** seguido de **instagram.com** seguido de **twitter.com** . Cuando **HIT** botón de retroceso, nos aterrizar en **Twitter** seguido por **instagram** seguido de **facebook** ._

<br/>

![[python/src/Diagram.svg]]

<br/>

Para entenderlo en **python**, podemos hacer una pila desde 0, donde ingresamos un elemento en la lista, después otro y este se ingresa atrás del primero y se elimina el último en ingresar.

<br/>

```jupyter
class Stack:
    def __init__(self):
        self.items = []

    def get_items(self): 
        return self.items

    def push(self, item):
        self.items.insert(0, item)
    
    def pop(self):
        self.items.pop(0)
    
    def size(self):
        return self.items
```

<br/>

---

<br/>

## Cola

<hr class="subtitle"/>

> **primero en ENTRAR, primero en SALIR**

 *¿Alguna vez has ido a un **teatro** a comprar una **entrada**?*

 *La persona al frente de la **cola** puede obtener sus boletos **primero,** mientras que uno al **final** de la cola será el **último**. *  
 
<br/>

![[Cola.svg]]

<br/>

Para entenderlo en **python**, podemos hacer una cola desde 0, donde ingresamos un elemento en la lista, después otro y este se ingresa atrás del primero y se elimina el primero en ingresar.

``` jupyter
class Queue:
    def __init__(self):
        self.items = []
    
    def get_items(self):
        return self.items
    
    def enqueue(self, item):
        self.items.insert(0, item)
        
    def dequeue(self, item):
        self.items.pop()
    
    def size(self):
        return len(self.items)
```

<br/>

---

<br/>

## Deque

<hr class="subtitle"/>

> **Entrada / Salida desde cualquier extremo de la cola.**

Es una combinación de las **colas** y las **pilas**, donde se tiene la opción de ingresar o salir por delante o por atrás dela cola.

<br/>

![[Deque.svg]]