# MultiObjectiveMetaheuristicsDNA_Patterns
Resultados de Evaluación de Metaheurísticas Multiobjetivo para el Descubrimiento de Patrones en ADN


Contiene los siguientes archivos:

- numero_ejecuciones_HV_referencia.xlxs: Este archivo contiene el número de ejecuciones independientes en las que se alcanza el HV de referencia para cada instancia y para cada algoritmo.
Nota: Aparece ✓ si se alcanza en 31 de 31, aparece - si se alcanza en 0 de 31.

- mediana_y_rango_intercuartilico.xlxs: Este archivo contiene laediana y rango intercuartílico (IQR) del número de evaluaciones (NEval) realizadas por los algoritmos para llegar al valor de HV de referencia. Se muestra para cada instancia y para cada algoritmo.
Nota: En cada celda se presenta el formato: NEval10^04_{IQR10^04}, donde NEval indica la evaluacion mediana de las que alcanza el hv de referencia.

- ranking_algoritmos.xlxs: Este archivo muestra en su primera columna un resumen de numero_ejecuciones_HV_referencia.xlxs y en su segunda columna un resumen de mediana_y_rango_intercuartilico.xlxs. En la tercera columna aparace el ranking global por algoritmos teniendo en cuenta las columnas anteriores.
Nota: En cada columna aparece el valor donde cada algoritmo obtiene el mejor resultado y tras ello entre paréntesis aparece el valor donde obtiene el segundo mejor resultado.

- metricas_biologicas: Este archivo muestra los resultados en cuento a nSn, nPPV, nPC y nCC para la evaluación mediana en cuanto a valor de hipervolumen. Lo muestra para cada instancia y para el mejor y peor de los algoritmos previos según el resultado obtenido en ranking_algoritmos.xlxs, además de NSGA-III.

