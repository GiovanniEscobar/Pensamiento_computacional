## Ejercicio de un programa que calcula el promedio y el estatus (aprobado o reprobado), de un alumno de los siguientes tres grupos: grupo 1 (español, matemáticas, ciencias); grupo 2 (español, matemáticas, ciencias, inglés); grupo 3 (español, matemáticas, ciencias, inglés, música)
    Algoritmo promedio_condicionales_añadidas 
      definir nombre Como Caracter
      definir español Como Real
      definir mate Como Real
      definir ciencias Como Real
      Definir promedio Como Real
      Escribir "Ingresa tu nombre"
      Leer nombre
      Escribir "Ingrese la calificación de español"
      Leer español
      Si español>10 Entonces
        Escribir "Calificación no válida"
      SiNo
        Escribir ""
      Fin Si
      Escribir "Ingrese la calificación de matemáticas"
      Leer mate
      Escribir "Ingrese la calificación de ciencias"
      Leer ciencias
      promedio<-(español+mate+ciencias)/3
      Si promedio>=6 Entonces
        Escribir "El promedio de ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Aprobado"
      SiNo
        Escribir "El promedio de ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Reprobado"
      Fin Si
    FinAlgoritmo
![Diagrama condicionales](https://user-images.githubusercontent.com/125599397/221008893-145b02bd-c0a1-42b5-9628-b8ace454f6b0.jpg)
