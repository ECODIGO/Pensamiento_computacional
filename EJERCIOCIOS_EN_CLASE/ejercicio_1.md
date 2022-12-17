Ejercicio que calcula el tiempo que tarda en leer el nombre de la poblacion mundial
# ALGORITMO
DIAGRAMA
![image](https://user-images.githubusercontent.com/119757494/208264007-2f1d90f0-dcec-4da9-a768-1a7f37846120.png)
# PSEUDOCODIGO


    Algoritmo calc
      población=0
      tiempo_a_leer=2
      segundoss=0
      minutos=0
      horas=0
      días=0
      meses=0
      años=0
      Escribir "ingresa el número de la población que quieres evaluar"
      Leer poblacion
      segundoss=poblacion*tiempo_a_leer
      minutos=segundoss/60
      horas=minutos/60
      dias=horas/24
      años=dias/365

      Escribir "TE TARDARAS ",años," AÑOS EN LEER LOS NOMBRES DE ",poblacion," HABITANTES"

    FinAlgoritmo
