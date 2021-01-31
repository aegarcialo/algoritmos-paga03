
Algoritmo Volumen_cilindro
	//Se va a realizar el calculo del area y volumen de un cilindro
	//Se solcita el valor del radio del cilindro
	Escribir "Buen dia, para calcular el area y volumen de un cilindro, se requiere tener las siguienes medidas:"
	Escribir "El radio (r) y la altura (h)"
	Escribir "Por favor digite la medida del radio (r) en cms que tiene la base del cilindro a calcular"
	Leer radio
	//Ahora se solicta el valor de la altura
	Escribir "Muy bien, ahora por favor digite la medida de la altura en cms del cilindro a calcular"
	Leer altura
	//Aqui realiza el calculo del area del cilindro y se muestra en pantalla la formula y su resultado
	Escribir "Primero: El area de un cilindro es A = {2 * PI * r * (h+r)} y en este caso el A = " 2*PI*radio*(altura+radio) " cms²"
	Escribir "Segundo: El volumen de un cilindro es V = {PI * r^2 * h} y en este caso el V = " PI*radio^2*altura " cms³"
FinAlgoritmo
