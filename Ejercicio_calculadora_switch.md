##Algoritmo para calculadora con switch en lugar de condicionales

    Algoritmo calculadora_con_switch
      Definir num1 Como Real
      Definir num2 Como Real
      Definir operador Como Caracter
      Definir res Como Real
      Escribir "Ingresa el primer número" //Se puede omitir, ya que la mayoría sabe cómo usar una calculadora
      Leer num1
      Escribir "Escriba el símbolo del operador para: sumar: +  restar: - multiplicar: *  dividir: / " //Se puede omitir, más si al ejecutarlo existirán botones
      Leer operador
      Escribir "Ingresa el segundo número" //Se puede omitir, ya que la mayoría sabe cómo usar una calculadora
      Leer num2
      Segun operador Hacer
        "+":
          res<-num1+num2
        "-":
          res<-num1-num2
        "*":
          res<-num1*num2
        "/":
          Si num2=0 Entonces
            Escribir "no se puede dividir un número entre 0"
          SiNo
            res<-num1/num2
          Fin Si
        De Otro Modo:
          Escribir "operador no válido"
      Fin Segun
      Escribir "El resultado de ",num1,operador,num2," es igual a ",res
    FinAlgoritmo
![diagrama calculadora con switch](https://user-images.githubusercontent.com/125599397/221955481-665df203-5d2f-4fbd-990f-387ab7c8a4e2.jpg)
