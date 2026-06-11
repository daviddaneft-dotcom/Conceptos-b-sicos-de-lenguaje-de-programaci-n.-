# Programa python de los 2 Seudocódigo anteriores

## Calcular el promedio de 3 notas.
print("Promedio de 3 notas:.\n")
nota_1 = float(input("Ingrese la primer nota:"))
nota_2 = float(input("Ingrese la segunda nota:"))
nota_3 = float(input("Ingrese la tercer nota:"))
promedio = (nota_1 + nota_2 + nota_3)/3
print("El promedio del estudiante es:",round (promedio,))
if promedio >= 60:
	print("El estudiante aprobo.")
else:
	print("El estudiante reprobo.")
print("Fin.") 

## Calcular el area de un rectángulo 

print("AREA DEL RECTANGULO:")
print("\n")
base = float(input("Ingrese la base del rectangulo:"))
altura = float(input("Ingrese la altura del rectangulo:"))
area = base * altura
print("La area del rectangulo es:", area)
