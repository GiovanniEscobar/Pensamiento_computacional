## Algoritmo para calcular el interés compuesto de un préstamo

    Algoritmo préstamo_int_comp
      Definir capital Como Real
      Definir tasa Como Real
      Definir tiempo Como Real
      Definir interes Como Real
      Definir total Como Real
      Escribir "Ingrese el capital inicial (préstamo)"
      Leer capital
      Escribir "Ingrese la tasa de interés anual como valor real"
      Leer tasa
      Escribir "Ingrese el tiempo en años"
      Leer tiempo
      total<-capital*(1+tasa)^tiempo
      interes<-total-capital
      Escribir "El interés generado es: ",interes
      Escribir "El monto total a pagar es: ",total 
    FinAlgoritmo

![image](https://user-images.githubusercontent.com/125599397/220739110-6505fc60-15ae-4183-9a73-dd42e57e2901.png)
![Diagrama sin título](https://user-images.githubusercontent.com/125599397/220739187-abb14de1-4814-4d10-a82c-14aeabc9e2c5.jpg)
