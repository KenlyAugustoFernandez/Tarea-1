Algoritmo ConversionUnidadesLongitud
    Definir centimetros, metros, yardas, varas, pulgadas, pies Como Real
    Definir unidad_objetivo Como Cadena
	
    Escribir "Ingrese la longitud en centimetros:"
    Leer centimetros
	
    Escribir "Opciones para trabajar : metros, yardas, varas, pulgadas, pies"
    Escribir "A qué unidad desea convertir:"
    Leer unidad_objetivo
	
    Si unidad_objetivo = "metros" Entonces
        metros <- centimetros / 100
        Escribir metros, " metros"
	Sino Si unidad_objetivo = "yardas" Entonces
			yardas <- centimetros / 91.44
			Escribir yardas, " yardas"
		Sino Si unidad_objetivo = "varas" Entonces
				varas <- centimetros / 50.8
				Escribir varas, " varas"
			Sino Si unidad_objetivo = "pulgadas" Entonces
					pulgadas <- centimetros / 2.54
					Escribir pulgadas, " pulgadas"
					
				Sino Si  unidad_objetivo = "pies" Entonces
						pies <- centimetros / 30.48
						Escribir pies, " pies"
					Sino
						Escribir "Sistema de medicion no coincide"
					FinSi
				FinSi
			FinSi
		FinSi
	FinSi
	
FinAlgoritmo
