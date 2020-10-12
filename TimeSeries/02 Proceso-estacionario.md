Proceso estacionario
----------------------------------------------

Para hacer inferencia estadística sobre la estructura de un proceso
estocástico sobre la base de un registro observado de ese proceso,
normalmente debemos hacer algunas suposiciones simplificadas sobre esa
estructura. La suposición más importante de este tipo es la de la
estacionariedad. La idea básica de la estacionariedad es que las leyes
de probabilidad que rigen el comportamiento del proceso no cambian con
el tiempo. En cierto sentido, se dice que el proceso está en equilibrio
estadístico.

Diremos que un proceso estocástico (serie temporal) es estacionario en
sentido estricto si:

(*X*<sub>1</sub>, *X*<sub>2</sub>, *X*<sub>3</sub>, ..., *X*<sub>*n*</sub>) y (*X*<sub>1 + *h*</sub>, *X*<sub>2 + *h*</sub>, *X*<sub>3 + *h*</sub>, ..., *X*<sub>*n* + *h*</sub>)

tienen la misma distribución para todos los enteros *h* y *n* &gt; 0.

Esta condición establece que la media y la varianza de todas las
variables son las mismas, además impone la condición de que la
dependencia entre las variables aleatorias
(*X*<sub>1</sub>, *X*<sub>2</sub>, *X*<sub>3</sub>, ..., *X*<sub>*n*</sub>)
y
(*X*<sub>1 + *h*</sub>, *X*<sub>2 + *h*</sub>, *X*<sub>3 + *h*</sub>, ..., *X*<sub>*n* + *h*</sub>)
es la misma, es decir sólo depende de la distancia *h*. En ese sentido,
puede notarse que para una muestra observada, el concepto de
estacionariedad en el sentido estricto es imposible de probar en el
práctica, por lo que se considera en su lugar la definición de proceso
estacionario en el sentido débil, el cual en la práctica es fácil de
contrastar.

Un proceso es estacionario en el sentido débil si se cumple que:

1.- *m*<sub>*x*</sub>(*t*) es independiente de *t*.

2.- *γ*<sub>*x*</sub>(*t* + *h*, *t*) es independiente de *t* para cada
*h*.

Este concepto implica la estabilidad de la media, la varianza y la
covarianza a lo largo del tiempo.
