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

