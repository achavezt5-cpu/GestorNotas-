# GestorNotas-
El objetivo del sistema es facilitar la consulta de notas de los cursos que el 
estudiante lleva en su carrera, así como también poder verificar, si aprobó o 
reprobó el curso de igual manera el estudiante podrá verificar su promedio.
Este sistema va dirigido a los estudiantes de las diferentes carreras Universitarias 
y cubre la necesidad de consultar sus notas sin necesidad de hablar directamente 
con algún catedrático o sumar notas de parciales y zona para poder saber su nota 
final, en resumen le facilitara al estudiante verificar sus notas cuando guste.

REQUISITOS DEL SISTEMA 
Funcionales:
El menú de este sistema deberá ofrecer el Registrar un nuevo curso, Mostrar la 
nota de los cursos individualmente,  Mostrar todas las notas juntas. Buscar Curso 
por su nombre, Calcular el promedio general, Mostrar cursos  aprobados y 
reprobados 
No Funcionales:
El sistema se ejecuta en consola con Python 
No utilizar librerías externas 
Debe usar bucles y condicionales en pseudocodigo 


Pseudocodigo 

Algoritmo Menu_proyecto
	
	
	Definir Opcion Como Entero 
	Mientras opcion=6 Hacer 
		
		Escribir ' Gestor de notas academicas'
		Escribir '1. Registrar nuevo  curso >='
		Escribir '2. Mostrar la nota de los cursos individualmente'
		Escribir '3. Mostrar todas las notas juntas'
		Escribir '4. Buscar curso'
		Escribir '5.Calcular promedio general'
		Escribir '6 Salir '
		Escribir 'Seleccione una opcion'
		Leer Opcion 
		Si opcion=1  Entonces 
			Registrar nuevo curso
		Sino 
			Si opcion=2 entonces 
				mostrar las notas de los cursos individualmente
				
			SiNo
				si opcion=3 entonces 
					Mostrar todas las notas juntas
				SiNo
					si opcion =4 Entonces
						Buscar cursos
					Sino 
						si opcion =5 Entonces
							Calcular promedio general
						Sino 
							Si opcion=6 entonces 
								Salir
							SiNo
								Escribir 'La opcion es 
invalida, porfavor intente de nuevo'
								
							FinSi
						FinSi
					FinSi
				FinSi
				
			FinSi
		FinSi
	FinMientras
	
	
FinAlgoritmo

