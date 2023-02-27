# Reto-4-que-bendicion-ahhhh
Solución de el Reto no. 4
# Primer Punto
Nos pide plantear un algoritmo, con el que se puedan optener los numeros primos hasta un numero n, usando pseudocodigo y representandolo en diagrama de flujo

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

![image](https://user-images.githubusercontent.com/124606636/221457029-ee28bb36-9ac2-4ff2-a36e-fbe4e030bfb6.png)

# Segundo Punto
Nos pide plantear un algoritmo en el que se hallen las raices de un numero n atravez de un proceso matemarico, usando pseudocodigo y representarlo en diagrama de flujo

	Proceso sin_titulo
	Escribir " Ingrese un numero natural"
	Definir n Como Real
	Definir x Como Real
	Definir t Como real
	Leer n
	si n>0 Entonces
		t <- 2
		x <- n/t
		Mientras x<>t Hacer
			t <- (x+t)/2
			x <- n/t
		FinMientras
		Escribir "la raiz de ",n," es ",t
	SiNo
		Escribir "No tiene una raiz real"
	FinSi
	fin proceso

![image](https://user-images.githubusercontent.com/124606636/221457438-d60e05a1-a2ae-4e3a-aef8-1fe7dfea5dfe.png)

# meme random
![image](https://user-images.githubusercontent.com/124606636/221457959-365cc6a4-14c1-48f6-974c-5008d1f2b8bb.png)
