## Algoritmo para calcular el promedio de 4 calificaciones, solicitando nombre y las calificaciones   
    
    Algoritmo promedio
      nombre<-""
      prom<-0
      calificación_1<-0
      calificación_2<-0
      calificación_3<-0
      calificación_4<-0
      Escribir "ingrese su nombre"
      Leer nombre
      Escribir "ingresa la primera calificación"
      Leer calificación_1
      Escribir "ingresa la segunda calificación"
      Leer calificación_2	
      Escribir "ingresa la terecera calificación"
      Leer calificación_3	
      Escribir "ingresa la cuarta calificación"
      Leer calificación_4
      prom=(calificación_1+calificación_2+calificación_3+calificación_4)/4
      Escribir "el alumno ",nombre," tiene un promedio de ",prom
    FinAlgoritmo

##Algoritmo para_calcular_el_tiempo_en_leer_los_nombres_de_todo_el_mundo

	Algoritmo leer_habitantes
		habitantes<-0
		años_real<-0
		años<-0
		semanas_real<-0
		semanas<-0
		días_real<-0
		días<-0
		horas_real<-0
		horas<-0
		minutos_real<-0
		minutos<-0
		seg<-0
		Escribir "Ingresa el número de habitantes actual"
		Leer habitantes
		años_real=(habitantes/(60*60*24*365))
		Escribir años_real
		años=TRUNC(habitantes/(60*60*24*365))
		Escribir años, " años"
		semanas_real=(años_real-años)*52
		Escribir semanas_real
		semanas=TRUNC(semanas_real)
		Escribir semanas " semanas"
		días_real=(semanas_real-semanas)*7
		Escribir días_real
		días=TRUNC(días_real)
		Escribir días," días"
		horas_real=(días_real-días)*24
		Escribir horas_real
		horas=TRUNC(días_real)
		Escribir horas," horas"
		minutos_real=(días_real-días)*60
		Escribir minutos_real
		minutos=TRUNC(minutos_real)
		Escribir minutos," minutos"
		seg=TRUNC((minutos_real-minutos)*60)
		Escribir seg," segundos"
		Escribir ""
		Escribir "el tiempo que tardaría en leer los nombres de todo el mundo es de:",años, " años, ",semanas," semanas, ",días," días, ",horas," horas, ",minutos," minutos, y ",seg," segundos" 
	FinAlgoritmo
 
##Algoritmo para_calcular_el_tiempo_en_leer_los_nombres_de_todo_el_mundo 
 
	Algoritmo leer_habitantes_clase
		habitantes<-0
		tiempo_total<-0
		años<-0
		meses<-0
		mes_real<-0
		dias<-0
		dias_real<-0
		seg<-0
		seg_dia=60*60*24
		seg_mes=seg_dia*30
		seg_año=seg_mes*12
		Escribir "ingresa el número de habitantes"
		Leer habitantes
		tiempo_total=habitantes*1
		años=TRUNC(tiempo_total/seg_año)
		Escribir años, " años,"
		mes_real=tiempo_total MOD seg_año
		meses=TRUNC(mes_real/seg_mes)
		Escribir meses " meses,"
		dias_real=mes_real MOD seg_mes
		dias=TRUNC(dias_real/seg_dia)
		Escribir dias " días. y"
		seg=dias_real MOD seg_dia
		Escribir seg, " segundos"
		Escribir "Tardarías ", años, " años,",meses," meses, ",dias," días, y ",seg," segundos" 
	FinAlgoritmo    
