# Ejercicio 5
Se desea saber la cantidad de alumnos que pasaron una materia. Son 25 y la calificación aprobatoria es 7.

ANALISIS:

1.- Vamos a empezar pidiendo la calificación del alumno y, con una condicional, vamos a verificar que esté entre 0 y 10, ya que es el sistema de calificaciones que se utiliza en México.

2.- Si pasa la condicional, vamos a contar que el alumno ya ingresó su calificación con un contador (c).

3.- Con otra condicional vamos a verificar si el alumno aprobó o reprobó la materia, poniendo que si la calificación es mayor o igual a 7 lo cuente un contador de alumnos aprobados (ca) y si no que lo mande al siguiente paso.

4.- Con una condicional vamos a crear un ciclo, escribiendo que si el contador es menor a 25 entonces se repita el proceso en el que un alumno ingresa su calificación, de otro modo que lo mande al siguiente paso.

5.- Ya al haber pasado los 25 alumnos, se nos imprimirá en pantalla el contador de alumnos aprobados, descartando así a los que sacaron menos de 7.

# DIAGRAMA DE FLUJO
![alumnos_aprobados EJ 5](https://github.com/ChristianDavSS/Portafolio/assets/145722756/e35da66d-2c50-48bb-b3b3-42d06593c004)

# PRUEBA DE ESCRITORIO
![Prueba de escritorio 5](https://github.com/ChristianDavSS/Portafolio/assets/145722756/62735d45-1735-41c6-826b-4624d8b0fc90)
