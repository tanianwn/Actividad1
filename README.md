# Actividad1

Este repositorio contiene el desarrollo de la Actividad 1, cuyo objetivo es obtener el vector de velocidades lineal y angular de un robot planar de tres grados de libertad (3GDL).

El procedimiento realizado incluye:

1. Definición simbólica de las variables articulares y parámetros geométricos.
2. Modelado cinemático del robot mediante matrices de transformación homogénea.
3. Obtención de la posición del efector final respecto al sistema de referencia inercial.
4. Cálculo del Jacobiano lineal mediante el método diferencial.
5. Cálculo del Jacobiano lineal y angular mediante el método analítico.
6. Determinación de las velocidades lineal y angular del efector final a partir del Jacobiano y las velocidades articulares.

El código fue implementado en MATLAB utilizando cálculo simbólico, lo que permite obtener expresiones generales de la cinemática diferencial del robot.
