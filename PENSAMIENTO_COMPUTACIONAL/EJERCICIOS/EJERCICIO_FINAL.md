Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

*1 inicio

*2 declarar num, num2, contador

*3 asignar num=azar(100)+1 contador=10

*3 mostrar "ingresa un numero"

*4 asignar num2

*5si num2==num1 mostrar("felicidades, adivinaste el numero en " opor "intentos" sino mientras contador <=0 mostrar ingresa un numero

Algoritmo Numero_secreto
	
	num1<- Azar(100)+1
	
	contador<-10
	
	Mientras contador >0 Hacer
		
		Escribir "ingresa un numero"
		
		Leer num2
		
		Si num1==num2 Entonces
			
			Escribir "Felicidades adivinaste el numero"
			
			contador<-0
			
		SiNo
			contador<-contador-1
			
			Si contador==0 Entonces
				Escribir "Fallaste, el numero secreto era ", num1
				
			SiNo
				Escribir "Fallaste, te qudan ",contador, " intentos"
				
			Fin Si
			
		Fin Si
		
	Fin Mientras
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203615/161421726-f14e9bfd-d90e-45a2-ae84-6a44ce8494f7.png)


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
