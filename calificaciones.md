Algoritmo Calculo_nota_ponderada
	//Se va a realizar el calculo de la nota final de un estudiante ponderada
	//Se solcita el valor de la priemra nota
	Escribir "Buen dia, para calcular la nota final, se solicitaran 4 notas"
	Escribir "Escriba nota del parcial 1"
	Leer parcial1
	//Se solcita el valor de la segunda nota
	Escribir "Escriba nota del parcial 2"
	Leer parcial2
	//Se solcita el valor de la tercera nota
	Escribir "Escriba nota de participacion"
	Leer participacion
	//Se solcita el valor de la cuarta nota
	Escribir "Escriba nota del examen final"
	Leer final
	//Se explica como se calcula la nota final
	Escribir "La Nota final se calcula:"
	Escribir "Parcial 1:25% - Parcial 1 = (" parcial1 ")"
	Escribir "Parcial 2:25% - Parcial 2 = (" parcial2 ")"
	Escribir "Participacion:20% - Participacion = (" participacion ")"
	Escribir "Examen final:30% - Examen final = (" final ")"
	//Se muestra la nota final
	Escribir "La nota final del estudiante es (" parcial1*.25+parcial2*.25+participacion*.2+final*.3 ")"
 FinAlgoritmo
