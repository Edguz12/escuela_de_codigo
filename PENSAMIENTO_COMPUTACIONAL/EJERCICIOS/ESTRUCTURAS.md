# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo

1 inicio

2 declarar numero float

3 mostrar "ingresa un numero"

4 si el numero es mayor a cero mostrara ("tu numero es positivo) 
si no mostrara ("el numero es negativo")
si es cero mostrara ("ingresa un numero valido")

5 fin

![image](https://user-images.githubusercontent.com/101203615/159041368-1a319a92-78a3-43ce-89cd-5cfcdd1fcbeb.png)


* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

1 inicio

2 declarar char

3 mostrar ("ingresa una letra que sea s o n")

4 si el caracter es s || n mostrara "caracter valido" 
si no mostrara "caracter invalido"

5 fin

![image](https://user-images.githubusercontent.com/101203615/159043150-6b588d98-561f-457f-a816-4669d0be4473.png)


* Un programa que pida una letra y detecte si es una vocal. 

1 inicio

2 declarar letra

3 mostrar ("ingresa una letra")

4 asigno letra

5 en caso de que (letra) haga caso a: mostrar ("vocal") caso e: mostrar ("vocal") caso i: mostrar ("vocal") caso o: mostrar ("vocal") caso u: mostrar ("vocal") si no mostrar "letra no valida"

6 fin

![image](https://user-images.githubusercontent.com/101203615/159047610-69e4f98f-ce5d-46e7-9dec-c1dcb8f7a412.png)


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

*1 inicio

*2 declarar num1, num2, num3

*3 mostar "ingresa un número"

*4 asignar num1 

*5 mostrar "ingresa otro número"

*6 asignar num2

*7 mostar "ingresa otro número"

*8 asignar num3

*9 si num1 < num2 y num1 < num3 y num2 < num3 mostar (num1, num2, num3) si no mostar(num1,num3,num2) si num2 < num1 y num2 < num3 y num1 < num2 mostrar (num2, num1, num3) si no mostrar(num2, num3, num1) si num3 < num1 y num3 < num2 si num1 < num2 mostar (num3, num1,num2) si no mostar(num3,num2,num1) sino mostrar ("se repitio algún número")

*10 fin

* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

*1 inicio

*2 declarar num

*3 mostar("ingresa un numero")

*4 asignar num

*5 en caso de num caso1: mostar("enero") caso2: mostar("febrero") caso3: mostar("marzo") caso4: mostar("abril") caso5: mostar("mayo") caso6: mostar("junio") caso7:mostar("julio") caso8: mostar("agosto") caso9: mostar("septiembre") caso10: mostar("octubre") caso11: mostar("noviembre") caso12: mostar("diciembre") sino mostar("no corresponde a un mes") 

*6 fin

* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

*1 inicio

*2 declarar (voto)

*3 mostar("escoge un partido: A(PARTIDO ROJO, B(PARTIDO VERDE), C(PARTIDO AZUL)")

*4 asignar(voto)

*5 SI(voto == "A")  mostar("usted voto por el partido ROJO") sino si(voto == "B") mostrar("usted voto por el partido VERDE") sino si(voto == "C") mostar("usted voto por el partido AZUL") sino mostar("voto invalido")

*6 fin

Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.

*1 inicio

*2 declarar(email,contra,email_validar,contra_validar)

*3 asignar(email_contra)

*4 asignar(contra_validar)

*5 mostrar("ingresa tu correo")

*6 asignar(email)

*7 mostrar("ingresa tu conraseña")

*8 asignar(contra)

*9 si(email == email_validar && contra == contra_validar) mostrar("email y contraseña correcta") sino mostar("email o contraseña incorrecta") 

*10 fin
