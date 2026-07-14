# MBA_Ising
Simulación de movimiento browniano, extendiendo el concepto a movimiento browniano anómalo para caracterización de series de tiempo volátiles

## Introducción

El objetivo de este proyecto es demostrar las limitantes reales de los modelos actuales ante series de tiempo altamente volátiles, o que por alguna causa violentan alguno de los supuestos conocidos.

Para ello, con el objetivo de demostrar como este tipo de series de tiempo pueden existir, se realizan simulaciones de movimiento browniano, primero geométrico. Luego, cuando este sea insuficiente para el objetivo, se pasa al movimiento browniano fraccionario, donde aspectos como colas pesadas y memoria, además de volatilidad, son comunes. Finalmente, se llega a series de tiempo gobernadas por vuelos de Lèvy, donde la ergodicidad puede perderse, los propios eventos siguen leyes de potencia, y en términos generales, la mayoría de los métodos actuales son insuficientes.

Si bien no se explora la totalidad de posibles eventos, bastan los ejemplos para demostrar que la actual metodología puede ser insuficiente, y a veces engañosa.