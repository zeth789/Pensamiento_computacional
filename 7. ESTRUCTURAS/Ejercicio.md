1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
  
        1-inicio
        2-declarar:
          num1(int)
          num2(int)
        3-Si num1>num2
          Mostrar "Num1 es mayor a Num2"
        4-Si num2>num1
          Mostrar "Num2 es mayor a Num1"
        5-Si num1=num2
          Mostrar "Los números son iguales"
        6-fin
        
![image](https://user-images.githubusercontent.com/113545552/191820726-9bb83b3c-9e54-484f-a1c7-5e8353aa79ac.png)
![image](https://user-images.githubusercontent.com/113545552/191820761-2c18a0d7-ce34-47f4-9808-f1d3f14518a6.png)

        
2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

        1-inicio
        2-declarar
          cal1(float)
          cal2(float)
          cal3(float)
          cal4(float)
          prom(float)
       3-Validar si:
          cal1, cal2. cal3. cal4 sean >0 y <10
       4-prom = (cal1 + cal2 + cal3 + cal4)/4
       5-Si prom > 5 si no
       
       Algoritmo sin_titulo
          cal1<-0
          cal2<-0
          cal3<-0
          cal4<-0
          prom<-0
          Escribir "Ingrese calificación 1"
          Leer cal1
          Si cal1>0 y cal1<=10 Entonces
            Escribir "Ingrese calificación 2"
            Leer cal2
            Si cal2>0 y cal2<=10
              Escribir "Ingrese calificación 3"
              Leer cal3
              Si cal3 > 0 y cal3 <= 10
                Escribir "Ingrese calificación 4"
                Leer cal4
                Si cal4 > 0 y cal4 <= 10
                  prom=(cal1+cal2+cal3+cal4)/4
                  Si prom > 6
                    Escribir "Calificación", prom,": Aprobado"
                  SiNo
                    Escribir "Calificación ",prom,": Reprobado"
                  FinSi
                FinSi
              FinSi
            FinSi
          Fin Si
        FinAlgoritmo

3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

       1-inicio
       2-Declarar
          num(int)
       2-Mostrar "Digite un número"
       3-Asignar num(int)
       4-Si num(num/2)==2 ? Escribir num, " es par": Escribir num, "es impar"
       5-fin
       
		       Algoritmo sin_titulo
			num=0
			Escribir "Digite un número"
			Leer num
			Si num/(num/2)==2
				Escribir num, " es par."
				Sino
					Escribir num, " es impar."
				FinSi
		FinAlgoritmo


 ![image](https://user-images.githubusercontent.com/113545552/192011011-a148c9e0-dbef-46e2-854b-f5fd5ce9cce1.png)
   
       
       

