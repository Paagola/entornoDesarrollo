### PRIMERA TAREA: FREIR UN HUEVO

Esta tarea consiste en hacer un algoritmo para hacer el paso a paso de hacer un huevo, hay que añadir dos tipos de bucles, un **if** y un **while**

Este programa está hecho en *PsInt*

```code

Proceso freirHuevo
	Definir huevo, aceite, sarten, sal, esthuev, resp Como Caracter;
	Definir cont Como Entero;
	resp <- "s";
	cont <- 0;
	Mientras Minusculas(resp) == "s" Hacer
		Escribir "VAMOS A FREIR UN HUEVO";
		Escribir "¿Tienes los ingredientes? s/n";
		Escribir "Huevo -" Sin Saltar;
		Leer huevo;
		Escribir "Aceite -" Sin Saltar;
		Leer aceite;
		Escribir "Sal -" Sin Saltar;
		Leer sal;
		Escribir "Sartén -" Sin Saltar;
		Leer sarten;

		Si Minusculas(huevo) == "s" y Minusculas(aceite) == "s" y Minusculas(sal) == "s" y Minusculas(sarten) == "s" Entonces
			Escribir "¿El huevo está en buen estado? s/n" ;
			Leer esthuev;
			si Minusculas(esthuev) == "s" Entonces
				Escribir "1. Pon la sartén en la vitro";
				Esperar 2 Segundos;
				Escribir "2. Enciende la vitro";
				Esperar 2 Segundos;
				Escribir "3. Pon aceite en la sartén";
				Esperar 2 Segundos;
				Escribir "4. Rompe el huevo y hechalo en la sartén";
				Esperar 2 Segundos;
				Escribir "5. Mientras el huevo se frie hecha un poco de sal";
				Esperar 2 Segundos;
				Escribir "6. Cuando veas que el huevo esté hecho retiralo y ponlo en un plato";
				Esperar 2 Segundos;
				Escribir "TAREA COMPLETADA!!";
				Esperar 1 Segundos;
				Escribir "¿Deseas hacer otro huevo?";
				Leer resp;
				cont <- cont + 1;
				Limpiar Pantalla;
			Sino 
				Escribir "Coje otro huevo!!";
				Limpiar Pantalla;
			FinSi
		Sino
			Limpiar Pantalla;
			Escribir "¿Quieres hacer un huevo? s/n";
			Leer resp;
			Limpiar Pantalla;
		FinSi
	FinMientras

```


