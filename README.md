# Reto-4-que-bendicion-ahhhh
Solución de el Reto no. 4
# Primer Punto
Nos pide plantear un algoritmo, con el que se puedan optener los numeros primos hasta un numero n, usando pseudocodigo

Algoritmo primos
	Definir z Como Entero
	Definir n como entero 
	definir x Como Entero
	definir r como entero 
	z=2
	x=1
	r=0
	Leer n
	Mientras z<=n Hacer
		mientras x<=z hacer	
			si z mod x=0 Entonces
				r=r+1
			FinSi
			x=x+1
		FinMientras
		x=1
		si r>2 Entonces
			escribir z, " no es primo"
		SiNo
			escribir z, " si es primo"
		FinSi
		r=0
		z=z+1
	FinMientras
FinAlgoritmo
