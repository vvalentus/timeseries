# Series de tiempo

## $\mathtt{Sobre\;el\;ejercicio}$

1. Considere la serie de tiempo asociada con los futuros de una de las criptomoneda desde que comenzó a comercializarse hasta la fecha del día de hoy. Utilice la API de Yahoo Finance para obtener esta serie de tiempo.

2. Repita TODOS los pasos indicados en esta sección para encontrar modelos ARIMA para predecir el precio de Cripto con los siguientes horizontes: 7, 14, 21 y 28 días. Utilizar siempre predicciones usando rolling con ventana de predicción continua de un día. 

3. Repita el paso 2 ahora sin utilizar rolling. Esto es, realice el pronóstico solo utilizando forecast() para los diferentes horizontes de predicción, 7, 14, 21 y 28 días.

4. Realice tablas de error para los ítems 1 y 2, utilizando las métricas: MAPE, MAE, RMSE, MSE, R2. Además, agregue el gráfico de correlación entre la observación real y su predicción en el test.

5. Repita el análisis desarrollado en los pasos anteriores, considerando ahora el criterio de inferencia Bayesiana (BIC) y el criterio de información de Hannan–Quinn (HQIC) para encontrar el mejor modelo ARIMA y, compare los errores con aquellos obtenidos con el criterio de Akaike.

6. Escriba en cada paso las conclusiones y análisis estadísticos asociados con los resultados obtenidos. Realice tests de normalidad e independencia para los residuales obtenidos para cada predicción, en cada caso agregue las correspondientes conclusiones. Figuras y algoritmos que no estén acompañados de una conclusión, descripción y análisis estadístico, no serán tenidas en cuenta.
