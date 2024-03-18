# Ejercicios

## Ejercicio I - Inversor de 3 bits

Armar un circuito que invierta o no tres entradas de acuerdo al valor de una entrada
adicional que actúa como control. En otras palabras, un inversor de k-bits es un circuito
de $k + 1$ entradas ($e_k, ..., e_0$) y $k$ salidas ($s_{k−1}$, ..., $s_0$) que funciona del siguiente modo:
- Si $e_k = 1$, entonces $S_i$ = $e_i ∀i < k$
- Si $e_k = 0$, entonces $S_i$ = $e_i ∀i < k$

Ejemplo:
inversor(1,011)=100 inversor(0,011)=011
inversor(1,100)=011 inversor(1,101)=010
2

## Ejercicio II - Sumador Simple

Armar un sumador de 1 bit. Tiene que tener dos entradas de un bit y dos salidas, una
para el resultado y otra para indicar si hubo o no acarreo.

## Ejercicio III - Sumador Completo

Teniendo dos sumadores simples (de 1 bit) y sólo una compuerta a elección, arme un
sumador completo. El mismo tiene 2 entradas de 1 bit y una tercer entrada interpretada
como CIn, tiene como salida COut y S. 

## Ejercicio IV - Shift

Armar un circuito de 3 bits. Este deberá mover a izquierda o a derecha los bits de entrada
de acuerdo al valor de una entrada extra que actúa como control. En otras palabras, un
shift izq-der de k-bits es un circuito de $k + 1$ entradas $(e_k, ..., e_0)$ y $k$ salidas ($s_{k−1}
, ..., s_0$)
que funciona del siguiente modo:
• Si $e_k = 1$, entonces $S_i$ = $e_{i−1}$ para todo $0 < i < k$ y $s_0 = 0$
• Si $e_k = 0$, entonces $S_i$ = $e_i+1$ para todo $0 ≤ i < k − 1$ y $s_{k−1} = 0$
Ejemplos:
shift_lr(1,011) = 110 shift_lr(0,011) = 001
shift_lr(1,100) = 000 shift_lr(1,101) = 010

### Resolucion 
- Solucion grafica en logisim en archivo .circ
