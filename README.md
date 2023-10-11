#pide al usuario que ingrese un numero entero y luego calcula la suma
numero = int(input("Ingrese un nuero: "))
print("Numeros pares: ")
contador_par = 2
while contador_par <= numero:
  print(contador_par)
  contador_par += 2
  
print("Numeros impares:")
contador_impar = 1
while contador_impar <= numero:
  print(contador_impar)
  contador_impar += 2
