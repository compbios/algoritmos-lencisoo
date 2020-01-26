# Volumen y área de un cilindro 
### Leonardo Enciso 
Comparto mi código para calcular el área y volumen de un cilindro

```Pseint 
Algoritmo CILINDRO 
	// Calculadora del area y volumen de un cilindro 
	// Escrito por Leonardo Enciso 
	// Maestria en bioestadistica - PUJ 
	Definir A Como Real 
	Definir B Como Real 
	
	Escribir "------------------------------------------"
	Escribir "CALCULADORA DE AREA Y VOLUMEN DEL CILINDRO" 
	Escribir "------------------------------------------"
	Escribir "Ingrese la altura del cilindro" 
	Leer A 
	Escribir "Ingrese el radio de la base del cilindro" 
	Leer B 
	
	AL<-2 * PI * B * A  // Calculo del área lateral 
	AT<- AL + (2 * PI * B^2) // Calculo del area total 
	VOL<-PI*B^2*A // Calculo del volumen
	
	Escribir "El area total del cilindro es: " ,AT
	Escribir "El volumen del cilindro es: " , VOL
	
FinAlgoritmo
```


