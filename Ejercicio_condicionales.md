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

## Ejercicio de un programa que calcula el promedio y el estatus (aprobado o reprobado), de un alumno de los siguientes tres grupos: grupo 1 (español, matemáticas, ciencias); grupo 2 (español, matemáticas, ciencias, inglés); grupo 3 (español, matemáticas, ciencias, inglés, música), validando las calificaciones que se encuentren entre 0 y 10:

        Algoritmo promedio_condicionales_añadidas
            definir nombre Como Caracter
            definir español Como Real
            definir mate Como Real
            definir ciencias Como Real
            Definir ingles Como Real
            Definir musica Como Real
            Definir promedio Como Real
            Definir grupo Como Entero
            Escribir "Ingrese su nombre"
            Leer nombre
            Escribir "Ingrese su grupo"
            Leer grupo
            Si grupo==1 Entonces //Empieza el grupo 1
                Escribir "Ingrese la calificación de español" 
                Leer español
                Si 0<=español Y español<=10 Entonces
                    Escribir "Ingrese la calificación de matemáticas"
                    Leer mate
                    Si 0<=mate Y mate<=10 Entonces
                        Escribir "Ingrese la calificación de ciencias"
                        Leer ciencias
                        Si 0<=ciencias Y ciencias<=10 Entonces
                            promedio<-(español+mate+ciencias)/3
                            Si promedio>=6 Entonces
                                Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Aprobado"
                            SiNo
                                Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Reprobado"
                            Fin si	
                        SiNo
                            Escribir "Calificación no válida"
                        Fin Si

                    SiNo
                        Escribir "Calificación no válida"
                    Fin Si

                SiNo
                    Escribir "Calificación no válida"
                Fin Si

            SiNo
                Si grupo==2 Entonces //Empieza el grupo 2
                    Escribir "Ingrese la calificación de español" 
                    Leer español
                    Si 0<=español Y español<=10 Entonces
                        Escribir "Ingrese la calificación de matemáticas"
                        Leer mate
                        Si 0<=mate Y mate<=10 Entonces
                            Escribir "Ingrese la calificación de ciencias"
                            Leer ciencias
                            Si 0<=ciencias Y ciencias<=10 Entonces
                                Escribir "Ingrese la calificación de inglés"
                                Leer ingles
                                Si 0<=ingles Y ingles<=10 Entonces
                                    promedio<-(español+mate+ciencias+ingles)/4
                                    Si promedio>=6 Entonces
                                        Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Aprobado"
                                    SiNo
                                        Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Reprobado"
                                    Fin si	
                                SiNo
                                    Escribir "Calificación no válida"
                                Fin Si
                            SiNo
                                Escribir "Calificación no válida"
                            Fin Si

                        SiNo
                            Escribir "Calificación no válida"
                        Fin Si

                    SiNo
                        Escribir "Calificación no válida"
                Fin Si
                SiNo
                    Si grupo==3 Entonces //Empieza grupo 3
                        Escribir "Ingrese la calificación de español" 
                        Leer español
                        Si 0<=español Y español<=10 Entonces
                            Escribir "Ingrese la calificación de matemáticas"
                            Leer mate
                            Si 0<=mate Y mate<=10 Entonces
                                Escribir "Ingrese la calificación de ciencias"
                                Leer ciencias
                                Si 0<=ciencias Y ciencias<=10 Entonces
                                    Escribir "Ingrese la calificación de inglés"
                                    Leer ingles
                                    Si 0<=ingles Y ingles<=10 Entonces
                                        Escribir "Ingrese la calificación de música"
                                        Leer musica
                                        Si 0<=musica Y musica<=10 Entonces
                                            promedio<-(español+mate+ciencias+ingles+musica)/5
                                            Si promedio>=6 Entonces
                                                Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Aprobado"
                                            SiNo
                                                Escribir "El promedio del participante ",nombre," del grupo 1, es de ",promedio,", por lo tanto es Reprobado"
                                            Fin si	
                                        SiNo
                                            Escribir "Calificación no válida"
                                        Fin Si
                                    SiNo
                                        Escribir "Calificación no válida"
                                    Fin Si
                                SiNo
                                    Escribir "Calificación no válida"
                                Fin Si

                            SiNo
                                Escribir "Calificación no válida"
                            Fin Si

                        SiNo
                            Escribir "Calificación no válida"
                        Fin Si
                    SiNo
                        Escribir "El grupo no existe" //validación negativa grupo 3
                    Fin Si //Termina grupo 3
                Fin Si //Termina grupo 2

            Fin Si //Termina grupo 1

        FinAlgoritmo
        
![diagrama condicionales](https://user-images.githubusercontent.com/125599397/221064270-f488229a-4b66-4872-909e-fbd961786d77.jpg)
