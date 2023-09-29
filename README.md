# Almacena 30 números en un vector
vector_original = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30]

# Elevar al cuadrado cada valor almacenado en el vector
vector_resultante = []
for numero in vector_original:
  vector_resultante.append(numero ** 2)

# Imprimir el vector original y el vector resultante
print("Vector original:", vector_original)
print("Vector resultante:", vector_resultante) 
[DEBUG ON]
[DEBUG OFF]



# Almacena 25 números en un vector
import random

vector = []
for i in range(25):
  numero = random.randint(-100, 100)
  vector.append(numero)

# Contar cuantos números son ceros, negativos y positivos
ceros = 0
negativos = 0
positivos = 0
for numero in vector:
  if numero == 0:
    ceros += 1
  elif numero < 0:
    negativos += 1
  else:
    positivos += 1

# Imprimir el número de ceros, negativos y positivos
print("Ceros:", ceros)
print("Negativos:", negativos)
print("Positivos:", positivos)

# Calcular la suma de los negativos y la suma de los positivos
suma_negativos = 0
suma_positivos = 0
for numero in vector:
  if numero < 0:
    suma_negativos += numero
  else:
    suma_positivos += numero

# Imprimir la suma de los negativos y la suma de los positivos
print("Suma de los negativos:", suma_negativos)
print("Suma de los positivos:", suma_positivos)




# Almacena 20 números en un vector
import random

vector = []
for i in range(20):
  numero = random.randint(1, 100)
  vector.append(numero)

# Almacena los números del vector original en orden inverso en otro vector
vector_inverso = []
for i in range(len(vector) - 1, -1, -1):
  vector_inverso.append(vector[i])

# Imprime el vector resultante
print("Vector original:", vector)
print("Vector resultante:", vector_inverso)
[DEBUG ON]
[DEBUG OFF]

