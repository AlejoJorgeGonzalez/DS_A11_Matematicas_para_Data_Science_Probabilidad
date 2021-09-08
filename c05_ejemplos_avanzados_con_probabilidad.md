# EJEMPLO AVANZADOS CON PROBABILIDAD

## Paradoja ¿niño o niña?

- Una mujer tiene dos bebés donde el mayor es un varón.
- Una mujer tiene dos bebés donde uno de ellos es varón.

A primera vista parece que la información es la misma, que la mujer tiene dos bebés y uno es varón, pero tienen un sutil cambio gramatical que cambia las probabilidades por completo.

La pregunta a contestar es:

¿Cuál es la probabilidad de esta mujer tenga dos hijos varones?

![](./imagenes/img8.png)

El espacio muestral consta de dos variables, el primer niño con dos sexos, y un segundo niño también con dos sexos, por tanto el espacio muestral es de 2x2, 4 posibilidades. Por tanto la probabilidad de que los dos sean varones es:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(MM)=\frac{1}{4}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(MM)=\frac{1}{4}" title="\large P(MM)=\frac{1}{4}" /></a>

Se resuelve la pregunta con la primera información, es decir, que el mayor es varón.

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(MM|mayor\&space;M)=\frac{1}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(MM|mayor\&space;M)=\frac{1}{2}" title="\large P(MM|mayor\ M)=\frac{1}{2}" /></a>

Dado que ya sabemos que el primero es varón, el espacio muestral consta de 2 elementos, por tanto la probabilidad se convierte en 1/2.

Con respecto a la segunda información, donde uno de ellos es varón, cambia totalmente, ya que el espacio muestral se a amplia a 3 y la posibilidad de que los dos sean varones es:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(MM|alguno\&space;M)=\frac{1}{3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(MM|alguno\&space;M)=\frac{1}{3}" title="\large P(MM|alguno\ M)=\frac{1}{3}" /></a>

El problema de Monthy Hall

![](./imagenes/img9.png)

La paradoja consiste en que un participante tiene tres puertas al frente, el cuál solo uno de ellos tenía un premio sorpresa. 

Sin ninguna información la probabilidad de seleccionar la puerta correcta es de 1/3, pero cuando el participante escogía la puerta, el presentador abría una de la puerta que no había seleccionado el participante y que no tiene el premio, en este momento el presentador le pregunta al participante si desea seleccionar la misma puerta o desea cambiar, por tanto ahora se tiene una posibilidad de ganar el premio del 50%, ya que las puertas se reducen a 2.

Pero la realidad es que no se aumenta la probabilidad, y esto se puede observar en el siguiente cuadro:

![](./imagenes/img10.png)

Se agregan dos columnas mas, si el participante se mantiene o cambia de puerta, si el participante decide quedarse con la misma puerta, la probabilidad es

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(win|stay)=\frac{1}{3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(win|stay)=\frac{1}{3}" title="\large P(win|stay)=\frac{1}{3}" /></a>

Sin embargo, la posibilidad de ganar si cambio de puerta es:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(win|switch)=\frac{2}{3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(win|switch)=\frac{2}{3}" title="\large P(win|switch)=\frac{2}{3}" /></a>

Lo que muestra que la probilidad no es de 1/2, si no que el cambiar de puerta aumenta la probabilidad de ganar a 2/3.