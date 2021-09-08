# EJEMPLO DE CÁLCULO DE PROBABILIDAD

## Correlaciones de eventos

Se quiere saber los resultados de:

- A = {el resultado de lanzar un dado es 4}
- B = {el resultado de lanzar un dado es par}
- C = {el resultado de lanzar un dado es impar}

![](./imagenes/img4.png)

Se empieza por saber la posibilidad de un evento sencillo sin ninguna condicional, para el primera posibilidad A, es de 1/6. 

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A)=\frac{1}{6}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A)=\frac{1}{6}" title="\large P(A)=\frac{1}{6}" /></a>

Ahora, la posibilidad de obtener un número, si ya se sabe que cayo par, es de:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{1}{3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{1}{3}" title="\large P(A|B)=\frac{1}{3}" /></a>

Esto sucede porque sabemos que es par, es decir, la muestra baja a 3, y de estos solo queda una . Esta probabilidad es mas alta que la primera probabilidad A, esto muestra que le hecho de que B haya ocurrido, aumenta las posibilidades de que aumente A, los que significa que los eventos  A y B estan positivamente correlacionados.

Ahora, imagina que sucede C, es decir, cae un número impar, por tanto no hay posibilidad de que haya caido A porque la probabilidad de A es excluyente de C, porque el espacio muestral de C no contiene el elemento A

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A|C)=\frac{0}{3}=0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A|C)=\frac{0}{3}=0" title="\large P(A|C)=\frac{0}{3}=0" /></a>

Esto significa que A y C estan negativamente correlacionados. Esto muestra que el hecho de que sean excluyentes, no significa que dos probabilidades sean independientes, para este caso son muy dependientes uno del otro.

Juego de ruleta

![](./imagenes/img5.png)

Se tiene dos jugadores que juegan en la ruleta, la ruleta tiene 8 espacios donde puede caer una pelota, cada jugador puesta cada uno por 4 casillas.

![](./imagenes/img6.png)

El jugador 1 será el jugador rojo y el jugador 2 es el jugador azul, los dos jugadores son excluyentes, ya que un numero de uno no lo tiene el otro. Primero se calcula la probabilidad de que gane el jugador 1. De ahora en adelante el los numeros jugador 1 es A y del 2  es B

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A)=\frac{4}{8}=\frac{1}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A)=\frac{4}{8}=\frac{1}{2}" title="\large P(A)=\frac{4}{8}=\frac{1}{2}" /></a>

Se sigue con la probabilidad de que gane A dado que cayó B

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{0}{4}=0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{0}{4}=0" title="\large P(A|B)=\frac{0}{4}=0" /></a>

Esto es un evento excluyente

![](./imagenes/img7.png)

Ahora se cambia la decisión del jugador 2, donde su espacio de muestra es 4,5,6,7, compartiendo con A el elemento 4. 

Por tanto la probabilidad, de que gane el jugador 1, sabiendo que la pelota cayo en un espacio del jugador 2 es:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{1}{4}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(A|B)=\frac{1}{4}" title="\large P(A|B)=\frac{1}{4}" /></a>

Dado que esta probabilidad es menor a la probabilidad P(A), que es 1/2, se puede concluir que A y B son eventos negativamente correlacionados.