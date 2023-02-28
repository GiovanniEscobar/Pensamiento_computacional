## Algoritmo para una calculadora de 2 dígitos, que pregunte los números a: sumar, restar, multipliccar o dividir. Considerar que no se puede dividir entre 0, por lo tanto, se debe validar que el segundo número ingresado sea diferente de 0

    Algoritmo calculadora_2_digitos
      Definir num1 Como Real
      Definir num2 Como Real
      Definir operador Como Caracter
      Definir res Como Real
      Escribir "Ingresa el primer número"
      Leer num1
      Escribir "Escriba el símbolo del operador para: sumar: +  restar: - multiplicar: *  dividir: / "
      Leer operador
      Escribir "Ingresa el segundo número"
      Leer num2
      Si operador=="+" Entonces
        res=num1+num2
        Escribir "El resultado de la suma ",num1," + ",num2," es igual a ",res
      SiNo
        Si operador=="-" Entonces
          res=num1-num2
          Escribir "El resultado de la resta ",num1," - ",num2," es igual a ",res
        SiNo
          Si operador=="*" Entonces
            res=num1*num2
            Escribir "El resultado de la multplicación ",num1," * ",num2," es igual a ",res
          SiNo
            Si operador=="/" Entonces
              Si num2=0 Entonces
                Escribir "no se puede dividir un número entre 0"
              SiNo
                res=num1/num2
                Escribir "El resultado de ",num1," / ",num2," es igual a ",res
              Fin Si
            SiNo
              Escribir "Esta calculadora no puede realizar esa operación"
            Fin Si
          Fin Si
        Fin Si
      Fin Si
      
      
![diagrama calculadora](https://user-images.githubusercontent.com/125599397/221868405-8f924cd0-a1aa-44e3-a619-8b24f129d8f7.jpg)
