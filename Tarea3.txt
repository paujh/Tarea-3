#Daremos una lista ya fija para este ejercicio.
l1 = [0.05, 0.0632, 1.2, 5.35, 7.45, 1.098, 1.234, 4.562, 1.543, 0.076, 2.865, 0.654, 5.961, 4.632, 2.316, 8.521, 5.862, 4.21, 0.542, 2.864]
#Sacaremos el promedio de la lista ya dada.
suma = 0.0
for i in l1:
  suma = suma + i
promedio = suma/len(l1)
#Imprimiremos de una vez el promedio.
print("El promedio de los numeros de la lista es " + str(promedio))
#Iniciaremos el ciclo while para encontrar el primer numero mas grande en la lista, que el promedio.
i = 0
while l1[i]<=promedio:
  i = i+1
#Imprimiremos dicho numero.
print("El primer numero mayor que el promedio es " + str(l1[i]) + ", que esta en la posicion " + str(i+1))
