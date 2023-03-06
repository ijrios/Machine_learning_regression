La regresión lineal múltiple permite generar un modelo lineal en el que el valor de la variable dependiente o respuesta (Y
) se determina a partir de un conjunto de variables independientes llamadas predictores (X1
, X2
, X3
…). Es una extensión de la regresión lineal simple, por lo que es fundamental comprender esta última. Los modelos de regresión múltiple pueden emplearse para predecir el valor de la variable dependiente o para evaluar la influencia que tienen los predictores sobre ella (esto último se debe que analizar con cautela para no malinterpretar causa-efecto).

Los modelos lineales múltiples siguen la siguiente ecuación:
Yi=(β0+β1X1i+β2X2i+⋯+βnXni)+ei

β0
: es la ordenada en el origen, el valor de la variable dependiente Y
 cuando todos los predictores son cero.
βi
: es el efecto promedio que tiene el incremento en una unidad de la variable predictora Xi
 sobre la variable dependiente Y
, manteniéndose constantes el resto de variables. Se conocen como coeficientes parciales de regresión.
ei
: es el residuo o error, la diferencia entre el valor observado y el estimado por el modelo.
Es importante tener en cuenta que la magnitud de cada coeficiente parcial de regresión depende de las unidades en las que se mida la variable predictora a la que corresponde, por lo que su magnitud no está asociada con la importancia de cada predictor. Para poder determinar qué impacto tienen en el modelo cada una de las variables, se emplean los coeficientes parciales estandarizados, que se obtienen al estandarizar (sustraer la media y dividir entre la desviación estándar) las variables predictoras previo ajuste del modelo.
