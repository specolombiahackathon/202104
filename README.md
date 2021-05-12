# 202104
*Algoritmos de Clasificación*


**Reto BASE:**
1. determinar la variable FLUIDTYPE para el set de datos de test (clasificacion supervisada)
2. determinar los campos analogos para cada campo del set de datos de test, y definir el RF maximo esperado (clasificacion no supervisada)

**Reto AVANZADO:**
1. como para el reto BASE
2. como para el reto BASE, adicionalmente se dispone de datos de produccion. Definir una metrica de similutud de los campos analogos.
3. determinar la variable RECOVERY para el set de datos de test (clasificacion supervisada)
  
  
**Para validar sus respuestas, accedan a este enlace:**  
https://oooo.shinyapps.io/specolombiahackathon202104/
  
**Métricas de evaluación:**

1. FLUIDTYPE: numero de aciertos / numero de campos a evaluar (200)
2. RF: root-mean-square error (RMSE)
3. Métrica de Similitud: identificar el cutoff "optimo" generando una grafica de puntuacion del RF (punto 2) vs cutoff con minimo 5 puntos. En este caso se asignará 1 punto si se entrega la grafica y datos y cero puntos de lo contrario.
4. RECOVERY: numero de aciertos / numero de campos a evaluar (200)
  
Para el Reto Base, la puntuación final se calcula asi: **FLUIDTYPE * 40% + RF * 60%**   
Para el Reto Avanzado, la puntuación final se calcula asi:  **FLUIDTYPE * 20% + RF * 40% + Métrica de Similitud * 10% + RECOVERY * 30%**
