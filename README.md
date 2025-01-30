# Regresión lineal múltiple

Después de haber trabajado con la regresión lineal simple, es momento de tomar un reto mayor,
pero a la vez, mucho más adecuado para problemas reales: la regresión lineal múltiple. En esta
ocasión practicarás con una base de datos de la NASA, con la que trabajaron para tratar de
determinar perfiles aerodinámicos ideales ante distintas condiciones, como: la velocidad del
viento y ángulo de ataque del mismo.


Utilizaremos el archivo de nombre “A1.3 NASA.csv”, donde podrás encontrar información para
1,052 observaciones distintas, con 6 mediciones para cada una de ellas. Los datos se
descargaron del UCI Machine Learning Repository, y originalmente se publicaron en el NASA
Reference Publication 1218.


La base de datos cuenta con la siguiente información:
- “frecuencia”. Frecuencia, en Hz.
- “angulo”. Ángulo de ataque, en grados.
- “longitud”. Longitud de cuerda geométrica, en metros.
- “velocidad”. Velocidad de flujo libre, en metros por segundo.
- “espesor”. Espesor del desplazamiento en el lado de succión, en metros.
- “presion”. Nivel escalado de presión sonora, en dB.

Objetivo: 
    Aplicar regresión lineal múltiple para modelar la relación entre diferentes características aerodinámicas y el nivel de presión sonora, analizando la significancia de las variables predictoras y evaluando el desempeño del modelo en datos de entrenamiento y validación.

Este proyecto incluye los siguientes documentos:
- [Jupyter NoteBook](Regresion_Lineal_Multiple.ipynb)
- [Datos](NASA.csv)
- [Reporte en HTML](Regresion_Lineal_Multiple.html)
