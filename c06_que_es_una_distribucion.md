# ¿QUÉ ES UNA DISTRIBUCIÓN?

Para utilizar la probabilidad es necesario conocer de otra área de las matemáticas como son el cálculo, y en el cálculo la primera noción es el concepto de función.

![](./imagenes/img11.png)

Por tanto en la probabilidad lo que se hace es coger una X aleatoria y se le asigna un valor que son sus probabilidades, a esto se le conoce como distribución. Por tanto, la distribución es una función, en la cual se le asigna un X que es el espacio muestral, y a cada uno de estos elementos se halla su probabilidad.

Es común que:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;X\rightarrow&space;variable\&space;aleatoria" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;X\rightarrow&space;variable\&space;aleatoria" title="\large X\rightarrow variable\ aleatoria" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;x\rightarrow&space;valores\&space;posibles\&space;en\&space;el\&space;espacio\&space;muestral" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;x\rightarrow&space;valores\&space;posibles\&space;en\&space;el\&space;espacio\&space;muestral" title="\large x\rightarrow valores\ posibles\ en\ el\ espacio\ muestral" /></a>

![](./imagenes/img12.png)

El dominio de X pueden ser discretos, es decir se pueden contar sus elementos porque es un espacio finito como por ejemplo las caras de un dado o continuo donde el numero de elementos pueden ser infinito como por ejemplo la temperatura.

![](./imagenes/img13.png)

Un dominio continuo permite que sus valores puedan ser graficados en un plano cartesiano, lo cual es interesante por no solo se puede calcular la probabilidad en un punto dado, sino la probabilidad en una región, como por ejemplo la probabilidad en una región menor a un punto dado.

Dominio Continuo

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(X\leq&space;x)=\int_{X\leq&space;x}^{}&space;P(X)dx=C(x)\leftarrow&space;funcion\&space;de\&space;probabilidad\&space;acumuluda" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(X\leq&space;x)=\int_{X\leq&space;x}^{}&space;P(X)dx=C(x)\leftarrow&space;funcion\&space;de\&space;probabilidad\&space;acumuluda" title="\large P(X\leq x)=\int_{X\leq x}^{} P(X)dx=C(x)\leftarrow funcion\ de\ probabilidad\ acumuluda" /></a>

Este cálculo puede realizarse también en dominios discretos, pero no estaría dados por graficas con curvas, sino en histogramas, por lo que para hallar la probabilidad acumulada cambia de integrales a sumatorias.


Dominio Discreto

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(X\leq&space;x)=\sum_{X\leq&space;x}^{}&space;P(X)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(X\leq&space;x)=\sum_{X\leq&space;x}^{}&space;P(X)" title="\large P(X\leq x)=\sum_{X\leq x}^{} P(X)" /></a>

Por ultimo, también se puede hallar la probabilidad entre dos punto en un dominio continuo por medio de la siguiente ecuación:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{120}&space;\bg_white&space;\large&space;P(a\leq&space;X\leq&space;b)=\int_{a}^{b}&space;P(x)dx" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{120}&space;\bg_white&space;\large&space;P(a\leq&space;X\leq&space;b)=\int_{a}^{b}&space;P(x)dx" title="\large P(a\leq X\leq b)=\int_{a}^{b} P(x)dx" /></a>