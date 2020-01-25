# Calculadora de notas ponderadas
### Leonardo Enciso 
Comparto mi código para la calculadora de notas ponderadas 

```Pseint
Algoritmo Notas
	// Este programa calcula el promedio ponderado 
	// Escrito por Leonardo Enciso 
	// Maestria en bioestadistica PUJ 
	Definir A Como Real // Parcial 1 
	Definir B Como Real // Parcial 2 
	Definir C Como Real // Participacion 
	Definir D Como Real // Examen final 
	Escribir "-------------------------------"
	Escribir "Calculadora de notas ponderadas" 
	Escribir "-------------------------------"
	Escribir "ingrese numeros entre 0 y 5"
	Escribir "-------------------------------"
	
	Escribir "Ingrese la nota del primer parcial"
	Leer A 
	Si A > 5 o A < 0  Entonces
		Escribir "El valor debe estar entre 0 y 5"
	SiNo
		Escribir "Ingrese la nota del segundo parcial" 
		Leer B 
		Si B > 5 o B < 0 Entonces
			Escribir "El valor debe estar entre 0 y 5"
		SiNo
			Escribir "Ingrese la nota de participacion"
			Leer C 
			Si C > 5 o C < 0 Entonces
				Escribir "La nota debe estar entre 0 y 5"
			SiNo
				Escribir "Ingrese la nota del examen final" 
				Leer D
				Si D > 5 o D < 0 Entonces
					Escribir "La nota debe estar entre 0 y 5"
				SiNo
					PondA<- A*0.25 
					PondB<- B*0.25
					PondC<- C*0.20
					PondD<- D*0.30 
					Final<-PondA+PondB+PondC+PondD
					Escribir "La nota final es: " ,Final
				Fin Si
			Fin Si
		Fin Si
	Fin Si

FinAlgoritmo
```

Esta estructura esta formada por instrucciones Si - Entonces anidadas para poder evitar que el usuario ingrese valores menores de 0 (Negativos) o mayores de 5
