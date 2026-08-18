## Programaciones para el desarrollo de la Tarea 3 del Módulo VII del Diplomado en Introducción Analítica a la Ciencia de Datos

Módulo 7: Optimización en aprendizaje de máquina Tarea 3, agosto 2026
Fecha de entrega: 18 de agosto

# El entregable consiste en **dos actividades** en un notebook reproducible cada uno: 

# Actividad 3.1:
Aplicar el algoritmo *Online Gradient Descent* a la base de datos y evaluar su Regret.

1. Descripción del problema
2. Metodología
3. Resultados, tablas, gráficas
4. Conclusiones

Información 1:
Rentas de bicicletas por hora `Bike Sharing Demand` disponible en Scikit-learn.
Tenemos datos de la forma $$(x_t, y_t),$$ donde $x_t$ es un vector de características, $y_t$ el número de biciletas rentadas al tiempo $t$. 
Las base de datos contiene: las rentas de bicicletas por hora con 17,379 registros con las siguientes entradas: season, year, month, hour, holiday, weekday, workingday, weather, temp, feel_temp, humidity, windspeed, count.

Programación:
Tarea3_Alfaro_Badillo_Cruz_Perez_Rupit_.ipynb


# Actividad 3.2: 
1. Para el entorno estacionario y para el entorno no-estacionario probar con diferentes valores de $\epsilon$ y describir cómo afecta el algoritmo.
2. Para el entorno estacionario usar tasa de aprendizaje constante y describir lo observado con el desempeño del algoritmo.
3. Para el entorno no estacionario utilizar como tasa de aprendizaje $1/N(a)$ y describir lo observado con el desempeño del algoritmo.    

Información 2:
Ejercicio de probabilidades, de los aciertos que obtendría con diferentes probabilidades mostrando a un "usuario" contenido de "Deportes", "Noticias", "Tecnología" y "Entretenimiento"
