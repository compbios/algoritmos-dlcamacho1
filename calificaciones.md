Algoritmo Calculo_promedio_ponderado
	Escribir "Escriba la calificación del primer parcial";
	Leer nota1;
	ponderación1 <- nota1 * 0.25;
	Escribir " Escriba la calificación del segundo parcial";
	Leer nota2;
	ponderación2 <- nota2 * 0.25;
	Escribir "Escriba la calificación de participación";
	Leer nota3;
	ponderación3 <- nota3 * 0.2
	Escribir "Escribir la nota del parcial final";
	Leer nota4;
	ponderación4 <- nota4 * 0.3
	promedio_ponderado <- ponderación1 + ponderación2 + ponderación3 + ponderación4;
	Escribir "su nota final es ", promedio_ponderado;
FinAlgoritmo

